---
name: X account growth study
description: When the user wants to study a benchmark X/Twitter account's history (formats, hooks, timing, topics, growth over time) and turn it into a posting playbook and draft posts.
---
# Steps
1. Resolve the account: x `get_users_by_username` (user.fields=created_at,public_metrics,description). Note followers, tweet count, join date. Fetch any source post the user cites with `get_posts_by_id`.
2. Budget X reads first (limits are per-minute and per-day and shared with the user). Plan ≤~400 calls, ≤~20/min. Every call returns at most 25 posts, even if max_results is higher. On HTTP 429, wait 2–5 min and retry; give up after ~30 min of failures and analyze what you have.
3. Pull data (always `write_to_file: true`; copy each result into a project folder immediately; never glob the shared agent-tools dir, other agents write there):
   - Recent: `get_users_posts` id=<user id>, exclude=replies,retweets, paginate with pagination_token for a few pages.
   - History: `search_posts_all` query "from:<handle> -is:reply -is:retweet", one call per month (or per quarter / alternate months to save budget) back to the account's early-growth era. Note: results come newest-first within the window, so each call samples the END of the window; `sort_order: relevancy` did not change this in practice.
   - Replies: a sample with "from:<handle> is:reply" for 1–2 windows.
   - post.fields=created_at,public_metrics,attachments,referenced_tweets,note_tweet,conversation_id. Use note_tweet.text for long posts.
4. Parse: tool files wrap JSON in untrusted-data markers; slice from first "{" to last "}". Dedupe by id. Save posts.json + posts.csv (id, created_at, text, chars, media count, quote, thread, likes, rts, replies, quotes, bookmarks, impressions, url).
5. Analyze with medians (means are skewed by outliers), always report n:
   - Per year / era: volume and median likes/bookmarks (growth curve).
   - Length buckets (<80, 80–280, 281–600, >600); recent-era-only split too.
   - Media vs text; quote posts; lists; question vs statement first line; number / $ in first line.
   - Topic buckets via keyword regex (product, life, platform tactics, other).
   - Posting hour converted to the user's timezone.
   - Top 30 by likes and top 15 by bookmarks with first lines.
   - Repost evidence: near-identical first lines at different dates.
6. Caveats to state: sampling bias (month-end windows), bookmark/impression metrics are missing or zero for older posts, keyword topic tagging is rough, small n buckets.
7. Web research: search interviews/podcasts for the account's growth story and milestones; cite URLs; mark founder-reported numbers as such.
8. Deliverables:
   - report.md: growth stages, what worked with numbers, what applies vs not to the user's own account size/niche.
   - A growth-tips post draft built only from real numbers in the data ("I studied N posts..."), statement hook with a hard number, no links, honest about the user's own position. Include translation if the user's chat language differs.
   - A posting playbook: format mix, hook rules, cadence, timing.
9. Never fabricate stats; never post. Hand drafts to the user to publish.
