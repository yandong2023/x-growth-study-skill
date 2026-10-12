---
name: X post writer
description: Write, rewrite, and review X (Twitter) posts, long posts, threads, replies, and quote posts that grow an account. Covers topic choice, 30+ hooks with real examples, templates, formatting, media, timing, recycling, and a post-publish review loop. Every rule is based on a study of 1,044 original posts from a 210K-follower founder account (@tibo_maker, 2020–2026). Use it when drafting any post, when picking what to post this week, or when a post underperformed.
---

# X Post Writer

A practical writing guide for X. Every rule here is backed by real posts from one benchmark account. The examples are quoted from his posts, with likes (L), bookmarks (B), and a link.

---

## 0. Read this first: the evidence and its limits

**Source.** @tibo_maker (Tibo Louis-Lucas) is a bootstrapped SaaS founder. He built Tweet Hunter and Taplio, sold them to Lempire in 2022, and now runs several SaaS products. The account had about 212K followers in Oct 2026.

**Sample.** 1,044 original posts (no replies, no retweets) from Jan 2020 to Oct 2026, pulled through the X API.
- 2020–2022: the last ~25 posts of almost every month.
- 2023 onward: one month per quarter.
- The last ~2 weeks of the sample are nearly complete.

This is a *sample*, not the full history. He has 49K+ tweets in total.

**Metrics.** Medians are used throughout, because averages get dragged around by viral outliers. Bookmarks were not recorded before ~2023, so bookmark comparisons mostly reflect 2023–2026 posts.

**Markers used in this guide.**
- **[DATA]**: a finding computed from the sample, with n (the number of posts).
- **[DIRECTIONAL]**: a small sample (roughly n < 15). Treat it as a hint.
- **[GENERAL]**: standard practice with no support from this dataset. Use your own judgment.

**What the data cannot tell you:**
- Threads. The dataset has no reliable thread structure, because conversation ids were missing for many posts.
- Replies. The only reply data is one 25-reply sample from June 2021.
- Deleted posts and follower counts over time.
- Image content. The data only shows whether media was attached, not what the image showed.

**Growth context** (from his own posts in the sample, and public interviews):
- 2020: median 1 like per post (n=114). On 2020-11-22 he posted "Reached 1000 followers today 🔥🔥" (L3). x.com/tibo_maker/status/1330592109762637826
- Jun 2021: "How I grew from 0 to 4k followers by getting inspiration from the best." (L92). x.com/tibo_maker/status/1409860346320355334
- Median likes per post by year: 18 in 2021, 39 in 2022, 63 in 2023, 85.5 in 2024, 64 in 2025, 89 in 2026.
- Nov 2024: "I posted every day for 4 years. It brought me: 130k+ 𝕏 followers … a $8m exit … $100k+ MRR" (L476). x.com/tibo_maker/status/1862155900297097481
- Interviews: Tweet Hunter's first paying user came in May 2021. An influencer launch took it from $3K to $20K MRR in Sept 2021. He sold to Lempire in 2022 for $2M upfront plus earnouts.

**Lesson zero.** The first year looked like nothing: a median of 1 like. Do not judge a strategy by its first 3 months.

---

## 1. Core rules (one-screen summary)

1. **Put a hard number in line 1.** A $ figure in the first line: median 133.5 L / 49.5 B (n=46). All other posts: 37 L / 2 B (n=1,001). [DATA]
2. **State it. Don't ask it.** Question first lines: median 32 L (n=94). Statements: 40 L (n=953). [DATA]
3. **Write long when you want saves.** 281–600 characters: 90 L / 38 B. Under 280 characters: 28–39 L / 1–2 B. [DATA]
4. **Attach media.** With media: 60 L / 17 B (n=135). Text only: 33 L / 1 B (n=912). [DATA]
5. **Put the product inside a story, never in an ad.** Since 2024: product posts 62 L, non-product business posts 81 L, life posts 187 L [DIRECTIONAL, n=7].
6. **Curate and explain.** His #1 post was a curated "how X works" explainer: 8,219 L / 6,651 B. [DATA]
7. **Write original posts more than quote posts.** Quote posts: 22 L. Originals: 43 L. [DATA]
8. **Bare link posts die.** "built in [link] try it, it's really good": 8 L. [DATA, examples in §3.6]
9. **Recycle your winners, and expect less the second time.** One repost went from 1,529 L to 246 L. [DATA, §10]
10. **Post every day for years.** [DATA: the yearly curve above]

---

## 2. Format and length

### 2.1 Length table [DATA]

All posts:

| Characters | n | Median likes | Median bookmarks |
|---|---|---|---|
| < 80 | 219 | 28 | 1 |
| 80–280 | 746 | 39 | 2 |
| 281–600 | 74 | 90 | 38 |
| > 600 | 8 | 120 | 68 [DIRECTIONAL] |

2024 onward only (removes the early small-account years):

| Characters | n | Median likes | Median bookmarks |
|---|---|---|---|
| < 80 | 50 | 72 | 9.5 |
| 80–280 | 225 | 72 | 14 |
| 281–600 | 67 | 96 | 38 (all-years figure) |
| > 600 | 8 | 120 | 68 [DIRECTIONAL] |

**How to read this.**
- In the mature account, short posts and medium posts get about the same likes.
- Long posts win clearly on bookmarks, and bookmarks are the signal that a post was worth keeping.
- Short posts have the higher ceiling *and* the lower floor. Several of his top-likes posts are under 110 characters (Meta dev meme 103, "git push" meme 60, "I keep coming back to this picture" 107). Most short posts die.

### 2.2 Which format, by goal

| Goal | Format | Evidence |
|---|---|---|
| Saves / authority | 281–1,000+ character list or guide, or a curated resource with notes | "posted 6,000+ tweets since 2020" (1,079 chars): L1,202 / B2,332 |
| Raw reach / likes | Under 120 characters, plus a relatable image, meme, or clip | "* Meta paying $500k/y for senior dev *" (103 chars, media): L6,918 / B380 |
| Trust / follows | Personal win or failure story with numbers | "I had to face 2 shutdowns, 1 bankruptcy…": L1,529 / B998 |
| Replies / conversation | Direct invitation to share, with a reason to answer | "Are you building a startup? … Share the link and your one sentence pitch! 👇": L562 / B409 |

### 2.3 Line breaks and layout [DATA + GENERAL]

- Posts with 3 or more line breaks (2024+): median 88 L (n=227). Posts with fewer: 63 L (n=123). [DATA]
- Put one idea per line, with a blank line between blocks. His long posts read like this:
  ```
  posted 6,000+ tweets since 2020
  built an X growth tool and sold it for $10m

  so I pulled my own data to see what actually works on X right now

  short list 👇

  1. replies beat posts when you're small. ...
  ```
- Lists. Posts containing a numbered or bulleted list: 55 L / 8 B, against 37 L / 2 B without one. [DATA]
- Bullet styles he uses: `1.`, `•`, `-`, `→`, `✅`, `🤖`. Pick one style per post.
- Lowercase, casual tone (2024+): 81 L (n=155), against 73 L for sentence case. Basically equal. Use whichever fits your voice. [DATA]

### 2.4 Emoji [DATA]

- 2024+: posts with at least one emoji had a median of 68 L (n=169). Posts without: 88 L (n=181). Emoji do not help on average.
- He uses them as **signposts**, not decoration:
  - 👇 to point to the list or link
  - 🤯 for the surprising number
  - ✨ / 🚨 as launch brackets ("✨ Taplio X is OUT ✨", L347)
  - 😅 to soften a self-promo line
- Rule: at most 1–3 emoji, each doing a job.

### 2.5 Links [DATA]

- 2024+: posts with a link in the body had a median of 59 L (n=55). Posts without: 82 L (n=295).
- His near-zero posts are mostly link-dump follow-ups:
  - "more wisdom: [link] - delivered every week": L5
  - "built in [link] try it, it's really good": L8 and L13
  - "if you're serious about X, the SuperX extension is an absolute must have": L2
- Rule: the post must deliver its value without being clicked. Put the link in a reply, or after the value has landed.

---

## 3. Topic map

Shares in the sample (keyword-tagged, so approximate): business insight / other 70%, product 16%, X-growth tactics 12%, life 2%. Median likes since 2024: life 187 [DIRECTIONAL, n=7], tactics 91, business 81, product 62.

### 3.1 Curated explainers and "someone smart said X" — highest saves

He packages someone else's knowledge, adds one line of his own take, and attaches the media.

- "explain how Shazam works" / I had no idea / Karpathy is so right about this / custom explainer videos will change education. **L8,219 / B6,651**. x.com/tibo_maker/status/2105980242321924284
- "a YC partner who closed millions in founder-led sales just laid out her 8 rules for cold email". **L1,342 / B3,611**. x.com/tibo_maker/status/2103779177191063879
- "this is how Nikita Bier builds viral apps". **L1,152 / B2,881** (2 media). x.com/tibo_maker/status/2106301320848171339
- "Here's Sam Altman, Founder of OpenAI, on cold outreach: Very practical advice indeed." **L1,055 / B1,878**. x.com/tibo_maker/status/1829163380717781434
- "These guys just dropped a masterclass on how (and what) to focus as a startup founders. Tons of insights here. I've added my notes alongside." **L373 / B610**. x.com/tibo_maker/status/1891808592619290706
- "In 2018, Sahil Bloom didn't have a Twitter account. Today he has almost 700K followers. I studied his growth… 12 growth tips". **L376 / B528**. x.com/tibo_maker/status/1573626553002590208
- "the leaked MrBeast production doc has a great lesson for founders". **L319 / B294**. x.com/tibo_maker/status/2093269905000804527

Pattern: a famous name or object, plus a specific promise (a number of rules, or "how it works"), plus media, plus a short personal take.

### 3.2 Personal wins with numbers

- "I've sold 2 startups, cofounded 4, and scaled one to $1 million ARR / The secret: launching in 30 days / The 17 tools that will get you to launch FAST 👇". **L3,434 / B3,161**. x.com/tibo_maker/status/1540337710371688448
- "I had to face 2 shutdowns, 1 bankruptcy, and 7 winding years of hustle to finally have my first win - a $10M acquisition." **L1,529 / B998**. x.com/tibo_maker/status/1729497635487121541
- "before selling Tweet Hunter for $10m, I had a long talk with @levelsio / he almost convinced me not to do it". **L680 / B321**. x.com/tibo_maker/status/2093238410680946841
- "I posted every day for 4 years. It brought me: 130k+ 𝕏 followers…". **L476 / B124**.
- "THIS IS IT 🤯 In 1 year, we went from 0 to $1m ARR". **L463 / B145**. x.com/tibo_maker/status/1529441166990749697
- "3 years ago, I acquired Typeframes for $50,000 / and turned it into an asset generating $500,000 per month". **L445 / B231**. x.com/tibo_maker/status/2104526662910025988
- "2015-2019: 🤦‍♂️ Built 2 'next Facebook' startups… 2021-2025: 🎯 Built 30+ products". **L413 / B223**. x.com/tibo_maker/status/1926933888347095400
- "I started the year shipping 1 product per week / Quantity led to quality / $20k MRR!!!". **L357 / B65**. x.com/tibo_maker/status/1461368157818568705

Pattern: concrete milestones (counts, $, years), the struggle before the win, and one transferable lesson.

### 3.3 Life, relatable, and humor — highest likes per post

- "* Meta paying $500k/y for senior dev * / PM: page load is slow / Senior Dev fix 👇" + media. **L6,918**. x.com/tibo_maker/status/1829131328404570522
- "LOL!! Claude (via Cursor) randomly tried to update the model of my feature from OpenAI to Claude 🤯". **L3,748**. x.com/tibo_maker/status/1895408283818881505
- "I keep coming back to this picture / it puts a lot of things into perspective for me" + image. **L2,049 / B521**. x.com/tibo_maker/status/2108490225982775619
- "me when I write "git push" to Claude" + media. **L1,548**. x.com/tibo_maker/status/2104907857065881941
- "guys, I had no clue, but managing 7 SaaS with 2 kids while playing WoW 8 hours per day is so freaking hard". **L772**. x.com/tibo_maker/status/2104141537919615123
- "every week, I ship more than the full year I spent as a CTO… and still have time to take walks with my wife / I love this life". **L354**. x.com/tibo_maker/status/1991846742468272386
- "✨ new French tax ✨ … net in pocket is 36% of my profit". **L576**. x.com/tibo_maker/status/1991822187427209524
- "I am a developer for 12 years. I still pray for the Regex I want to be on Stackoverflow." **L578**. x.com/tibo_maker/status/1442041229131194370

Pattern: an in-group joke for your niche, or a moment from your real life with one specific detail (7 SaaS, 2 kids, 8 hours of WoW).

### 3.4 Tactics and opinions

- "posted 6,000+ tweets since 2020… short list 👇 1. replies beat posts…". **L1,202 / B2,332**.
- "AI isn't killing jobs. It's killing employment as we know it. My prediction: • The 9-5 will die…". **L793 / B301**. x.com/tibo_maker/status/1894016656319635956
- "pro tip: like posts from people < 1k followers / they'll see you in their notifs". **L413**. x.com/tibo_maker/status/1961009573151506837
- "Most founders you look up to aren't particularly special... They were just too stupid to quit." **L324**. x.com/tibo_maker/status/1792861397937733689
- "Most of the startup growth advice is horse shit." **L141 / B334**. x.com/tibo_maker/status/1763199702986543216
- "i had a weird realization recently… and then google p-max beat all of them". **L318 / B345**. x.com/tibo_maker/status/2058519964491952169
- "My full-time job at @TweetHunterIO is to discover the best strategies… analyzed 5,000+ accounts… blueprint to go from 100-10k FANS". **L543 / B1,039**. x.com/tibo_maker/status/1605884368521666563

### 3.5 Product posts that worked (the product shown inside a story)

- "Ferrari launched their first electric car / so I made a launch video for them / (using Revid obviously 😅)". **L733**. x.com/tibo_maker/status/2059499312472604877 (newsjacking + demo)
- "if anyone reading this can create this, DM me / I'll hire you instantly. / I need to do more on Revid". **L963 / B801**.
- "I am crying right now 🥲 / this guy uses 3 of my products and just reached 11k MRR". **L367 / B326**. x.com/tibo_maker/status/2108841747941925192 (customer win)
- "Outrank reached $120,000 MRR 😳 / what worked for us: ✅…". **L343 / B195**. x.com/tibo_maker/status/1960998387076960691 (milestone + lessons)
- "I just can't believe that this software that was making < $1000/m when I bought it, has now reached $200,000 ARR 🤯". **L340**. x.com/tibo_maker/status/1828029214345347431
- "new way to make an extra $50k+/year: 👉 sell backlinks on Outrank". **L364 / B466**. x.com/tibo_maker/status/2092166071654445257 (a money benefit for the reader)
- "I hired 7 AI agents this month & they've taken over my SaaS 😱 here's my actual org chart". **L367 / B444**. x.com/tibo_maker/status/2059930221680189744

Pattern: the reader's gain, a number, a story, or a news hook comes first. The product name comes later or in parentheses.

### 3.6 Product posts that flopped (anti-patterns)

- "built in [link] / try it, it's really good". **L8**. x.com/tibo_maker/status/2106686499865399586 (and L13 when posted again)
- "built by [link] which goes much further than just using Opus 5.5". **L6**.
- "if you're serious about X, the SuperX extension is an absolute must have". **L2**. x.com/tibo_maker/status/2109352693651427600
- "if you guys want to learn more about weird niche stuff, i've just created a new YT channel for this: [link]". **L2**.
- "I WILL BUY THIS 50,000 CAR 🤩 nano-banana-pro in Revid is seriously impressive". **L4**.
- "Sharing the playbook that turned years of failure into an $8m acquisition…" (newsletter CTA, posted 6 times in 8 days). **L0–7 each**. Even a strong number hook dies when it is a recurring ad.

What they share: a link plus an adjective ("really good", "must have"), and nothing the reader learns without clicking.

---

## 4. Hook library (36 patterns, all from his posts)

Format: **Pattern** — real first line(s) — metrics — when to use it.

### A. Number and money hooks
1. **Stacked credentials** — "I've sold 2 startups, cofounded 4, and scaled one to $1 million ARR" — L3,434 / B3,161. Opens a list or guide when you have real proof.
2. **Struggle tally → win** — "I had to face 2 shutdowns, 1 bankruptcy, and 7 winding years of hustle to finally have my first win - a $10M acquisition." — L1,529 / B998. Use for origin stories.
3. **Price tag on someone's time** — "Nikita Bier charges $500 a minute for advice" — L257 / B521. Makes free content feel valuable.
4. **Dollar setup for a joke** — "* Meta paying $500k/y for senior dev *" — L6,918. A big number makes the punchline land harder.
5. **Small spend, absurd result** — "handed my OpenClaw an API key with $40 in credits… burned through everything in 10 seconds" — L1,612. Good for AI and tool experiences.
6. **Buy low, grow high** — "3 years ago, I acquired Typeframes for $50,000 / and turned it into an asset generating $500,000 per month" — L445 / B231.
7. **Before → after revenue** — "this software that was making < $1000/m when I bought it, has now reached $200,000 ARR 🤯" — L340.
8. **Milestone + "what worked"** — "Outrank reached $120,000 MRR 😳 / what worked for us:" — L343 / B195.
9. **Reader money benefit** — "new way to make an extra $50k+/year:" — L364 / B466.
10. **Math breakdown** — "✨ new French tax ✨ … 67% * 55% * 97% = 36%" — L576. Show the calculation.
11. **Speculative math about a famous person** — "is it safe to assume @levelsio has $36m invested? 🤯" — L410 / B250. One of the few question hooks that works, because it carries a number and a famous name.
12. **Volume as credibility** — "posted 6,000+ tweets since 2020" — L1,202 / B2,332.
13. **Research volume** — "I've done all the research and analyzed 5,000+ accounts for you." — L543 / B1,039.
14. **Years of consistency** — "I posted every day for 4 years." — L476.

### B. Curated and explainer hooks
15. **Quoted ask + "how X works"** — ""explain how Shazam works"" — L8,219 / B6,651.
16. **Credentialed person + N rules** — "a YC partner who closed millions in founder-led sales just laid out her 8 rules for cold email" — L1,342 / B3,611.
17. **"This is how [famous person] does X"** — "this is how Nikita Bier builds viral apps" — L1,152 / B2,881.
18. **"Here's [famous person] on [topic]:"** — "Here's Sam Altman, Founder of OpenAI, on cold outreach:" — L1,055 / B1,878.
19. **Masterclass + my notes** — "These guys just dropped a masterclass on… I've added my notes alongside." — L373 / B610.
20. **Then vs now of a big account** — "In 2018, Sahil Bloom didn't have a Twitter account. Today he has almost 700K followers." — L376 / B528.
21. **Leaked or insider document** — "the leaked MrBeast production doc has a great lesson for founders" — L319 / B294.
22. **"Best resource" collection** — "built the best resource for your own Motion Graphics video / including the 50+ best videos" — L352 / B610.

### C. Story and confession hooks
23. **Emotional opener** — "I am crying right now 🥲" — L367 / B326.
24. **Weird realization** — "i had a weird realization recently" — L318 / B345.
25. **Private conversation with a famous peer** — "before selling Tweet Hunter for $10m, I had a long talk with @levelsio" — L680 / B321.
26. **Feeling behind → small win** — "you know this feeling when you see everyone doing amazing things, and it just drains all your energy…" — L478.
27. **Picture with perspective** — "I keep coming back to this picture" — L2,049 / B521.
28. **Absurd self-portrait** — "managing 7 SaaS with 2 kids while playing WoW 8 hours per day is so freaking hard" — L772.

### D. Contrarian and declarative hooks
29. **Reframe** — "AI isn't killing jobs. / It's killing employment as we know it." — L793 / B301.
30. **"Most X are…"** — "Most founders you look up to aren't particularly special..." — L324. "Most of the startup growth advice is horse shit." — L141 / B334.
31. **"People get this take wrong"** — L433. x.com/tibo_maker/status/1827615427779838001
32. **"pro tip:"** + a counterintuitive micro-tactic — "pro tip: like posts from people < 1k followers" — L413.
33. **Then/now timeline** — "2015-2019: 🤦‍♂️ … 2021-2025: 🎯" — L413 / B223.

### E. Engagement hooks
34. **Open stage** — "Are you building a startup? / Congrats! 👏 / Here's your chance. / Share the link and your one sentence pitch! 👇" — L562 / B409. One of only a handful of successful question openers: the question is a filter, and the ask is concrete.
35. **News + a poll of the crowd** — "it's done / X removed the ability to reply through the API / so tell me: are you seeing a huge reduction in AI replies today?" — L629.
36. **Hiring call as a showcase** — "if anyone reading this can create this, DM me / I'll hire you instantly." — L963 / B801.

### F. Anti-patterns (real low performers)

| Hook | Likes | Why it failed |
|---|---|---|
| "So where are you now? [link]" (2020) | 0 | Vague question, no context |
| "Does it help you prioritizing tasks or does it get you anxious?" (2020) | 0 | Question with no stake |
| "Never give up! [link]" (2020) | 0 | Generic motivation |
| "Don't wait for inspiration to come to you! act on your ideas now" (2020) | 1 | Platitude, no proof |
| "How to start your product in 5 steps:" (2020-12) | 1 | The list promise had no credentials behind it yet |
| "How I got 15% new followers with a single tweet" (2021-02) | 3 | A percent of a tiny base reads as weak |
| "What a thread!" / "Best thread I read in a very long time [link]" | 1 | Quote-praise that adds nothing |
| "built in [link] / try it, it's really good" (2026) | 8 | Bare product link |
| "more wisdom: [link] - delivered every week" | 5 | Newsletter ad |

Note the timing in the first rows. The same "How to" format got 1 like in 2020 and the "How I grew" version got 92 L in mid-2021. Proof and audience size change how a hook performs.

---

## 5. Teardowns of his top posts

### T1. "explain how Shazam works" — L8,219 / B6,651 (171 chars, media)
```
"explain how Shazam works"          ← a quoted prompt: curiosity + everyone knows Shazam
                                    
I had no idea                        ← honest reaction, 4 words, lowers status
                                    
Karpathy is so right about this      ← borrows authority, joins a live conversation
custom explainer videos will change education   ← the take: one-line prediction
[link] [video]                       ← the value is in the media
```
Why it worked: a universally known object, curiosity, an authority name, a short take, and a video worth saving. He did not make the claim himself; he curated it.

### T2. "* Meta paying $500k/y for senior dev *" — L6,918 (103 chars, media)
```
* Meta paying $500k/y for senior dev *   ← stage direction + big $ number
PM: page load is slow                    ← relatable setup
Senior Dev fix 👇                        ← points to the punchline media
```
Why it worked: meme format, an in-group joke for developers, and the dollar figure raises the stakes. Reach yes, saves no (B380).

### T3. "LOL!! Claude (via Cursor) randomly tried to update the model…" — L3,748
Structure: reaction word → a specific funny thing an AI tool did → a parenthetical showing it was unprompted → screenshot. Why: timely (AI coding tools), screenshot proof, and readers share it.

### T4. "I've sold 2 startups, cofounded 4, and scaled one to $1 million ARR" — L3,434 / B3,161 (151 chars)
```
I've sold 2 startups, cofounded 4, and scaled one to $1 million ARR   ← 3 stacked credentials
The secret: launching in 30 days                                      ← a single claim
The 17 tools that will get you to launch FAST 👇                      ← numbered resource promise
```
Why: credentials make the list believable, "17 tools" can be saved, and 👇 opens a thread or list.

### T5. "I keep coming back to this picture" — L2,049 / B521
Two short lines plus an image. Why: an emotional, reflective framing invites people to project their own meaning onto it. The image carries everything. Only works if the image is genuinely strong.

### T6. "handed my OpenClaw an API key with $40 in credits" — L1,612 (202 chars, text only)
```
handed my OpenClaw an API key with $40 in credits   ← small $ + action
asked a single question                             ← minimal input
agent burned through everything in 10 seconds       ← absurd outcome, a second number
still don't know what it actually did               ← honest confusion
imagine giving real money to those things           ← the take: a broader warning
```
Why: a micro-story with two numbers, a beat on every line, and a closing opinion.

### T7. "me when I write "git push" to Claude" — L1,548
A meme with the "me when" format and a niche in-joke. Pure reach.

### T8. "I had to face 2 shutdowns, 1 bankruptcy…" — L1,529 / B998 (250 chars)
```
I had to face 2 shutdowns, 1 bankruptcy, and 7 winding years of hustle   ← struggle tally
to finally have my first win - a $10M acquisition.                       ← big $ payoff
This is the first time I'm sharing the full story here.                  ← exclusivity
A thread on the reality of startup success 👇🏻                           ← thread promise
```
Why: a vulnerable story with a dramatic contrast between the failures and the $10M.

### T9. "a YC partner … 8 rules for cold email" — L1,342 / B3,611 (118 chars)
Authority + a proof claim ("closed millions") + a number of rules + media. A save ratio of 2.7 bookmarks per like. The best "save magnet" format in the dataset.

### T10. "posted 6,000+ tweets since 2020" — L1,202 / B2,332 (1,079 chars)
```
posted 6,000+ tweets since 2020                  ← volume credibility
built an X growth tool and sold it for $10m      ← $ credential
so I pulled my own data to see what actually works on X right now   ← method
short list 👇
1.–8. each item: rule + his own number          ← proof per item
(bookmark this post btw)                         ← explicit save CTA mid-post
on top of that, one core rule: ...               ← summary rule
this is a hard and long journey ...              ← honest close
```
Why: credentials + data + a numbered list + a number in every item + a bookmark CTA + an honest ending.

### T11. "this is how Nikita Bier builds viral apps" — L1,152 / B2,881 (65 chars, 2 media)
A short line, a famous operator, a "how" promise, and the value in the images. Saves are 2.5× likes.

### T12. "Here's Sam Altman, Founder of OpenAI, on cold outreach:" — L1,055 / B1,878
Name + title + topic + a colon, then a short take ("Very practical advice indeed. Even if you are a tech genius like him, you NEED reliable lead gen"), then the clip.

### T13. "if anyone reading this can create this, DM me" — L963 / B801
A hiring call is high-status social proof ("I'll hire you instantly"). It also showcases the work, and only then mentions the product ("I need to do more on Revid").

### T14. "AI isn't killing jobs." — L793 / B301 (381 chars)
```
AI isn't killing jobs.
It's killing employment as we know it.     ← reframe in 2 lines
My prediction:
• The 9-5 will die
• Big corps will shrink
• Solo creators will thrive
• Everyone becomes an entrepreneur
• The middle class splits into 2 groups: (sub-bullets)
The greatest wealth transfer of our time isn't crypto or stocks.
It's the ability to use AI effectively.   ← quotable closer, mirrors the opener
```

### T15. "guys, I had no clue, but managing 7 SaaS with 2 kids while playing WoW 8 hours per day…" — L772
Self-deprecating humor with 3 specific numbers. A humble brag that reads as a joke. Life content.

### T16. "Ferrari launched their first electric car / so I made a launch video for them" — L733
Newsjacking: big news → I made something with it → the product in parentheses with 😅. The product is the tool, not the message.

### T17. "My full-time job at @TweetHunterIO is to discover the best strategies…" — L543 / B1,039
Authority from his job + research volume (5,000+ accounts) + a promise of a "failproof blueprint" with a specific range (100–10k). Saves were 2× likes.

### T18. "Hey, all FAANG smart tech people…" — L670 / B1,001
Calls out a specific audience → a reframe ("have you tried Indie Making?") → a playbook promise with $ ("$1M/year one-person business").

### T19. "Nikita Bier charges $500 a minute for advice" — L257 / B521 (487 chars)
A price anchor → "only takes calls with VC-backed founders" (exclusivity) → "so we turned his whole … playbook into a free, open-source AI skill" (free value) → 4 bullets of what you get → CTA. A product launch disguised as access to an expert.

### T20. "Are you building a startup? Share the link…" — L562 / B409
A filtering question + congratulation + a concrete ask. It works because the reader gets free exposure by replying.

### What the top posts have in common
- A specific noun, name, or number early in line 1 (true of nearly all 20; judged by eye, not computed).
- Media on almost every top-reach post. Text-only top posts all carry numbers or a list.
- A personal one-line take next to curated content.
- The product named in at most 3 of the 20, and never in the first line.

---

## 6. Media guidance

[DATA]
- With media: median 60 L / 17 B. Text only: 33 L / 1 B.
- Of the top 10 posts by likes, 6 had media. Of the top 5 by bookmarks, 3 had media.
- The media types themselves were not captured, so the categories below are inferred from the post text.

Media types inferred from his top posts:

| Type | Example | Metrics |
|---|---|---|
| Explainer video or clip from an expert | "explain how Shazam works", Sam Altman clip | L8,219 / B6,651; L1,055 / B1,878 |
| Meme or reaction image | Meta senior-dev fix, "git push" | L6,918; L1,548 |
| Screenshot of an AI or tool doing something surprising | Claude via Cursor | L3,748 |
| Image or slides of someone's rules or playbook | YC cold email rules, Nikita Bier | B3,611; B2,881 |
| A reflective image ("this picture") | perspective picture | L2,049 |
| Product-made demo video | Ferrari launch video | L733 |
| Chart / graphic | "Average journey of a startup founder." | L725 |

Rules:
1. The media should be able to stand alone: the screenshot *is* the proof, the video *is* the value.
2. The post text frames the media in 1–3 lines. Don't repeat what the media shows.
3. For saves, use dense, reusable visuals (rules, frameworks, checklists, annotated screenshots).
4. For reach, use instantly readable visuals (memes, reactions, one striking picture).
5. [GENERAL] Crop screenshots to the point, make text readable on a phone, and use one focal point.

---

## 7. Threads and long posts

**What the data shows.**
- 31 posts in the sample say "thread" or 🧵 in the opener. Their median is 70 L, against 40 overall [DATA]. Top examples:
  - "I had to face 2 shutdowns…" (L1,529)
  - "Imagine being early on crypto… 5 predictions" (L352)
  - "Why now is the best time to bootstrap a million dollar startup" (L274)
- Thread *bodies*, meaning the posts after the first, could not be analyzed.
- Since 2023 he has mostly moved to single **long posts** (280–1,100 chars) instead of threads. His best-saved recent list, the 1,079-character "6,000+ tweets" post, is a single long post.

[GENERAL] How to write a thread when you need one:
1. Post 1 does all the work: hook + promise ("17 tools", "12 growth tips", "the full story"). End with 👇.
2. One idea per post. Each post must make sense on its own when it is screenshotted.
3. Number the posts or items, so readers know their progress.
4. Put proof (an image or number) in at least every 2–3 posts.
5. The last post summarizes in one line plus a soft CTA (follow / bookmark / a link). His recurring newsletter CTA got L0–7, so keep the CTA short and only after delivering value.
6. Prefer a single long post if it fits in ~1,500 characters. It is simpler, and the whole thing gets read.

---

## 8. Replies and quote posts

**What the data shows (limited).**
- Quote posts: median 22 L (n=196). Originals: 43 L [DATA].
- His replies in a June 2021 sample (n=25): median 1 L, max 3 [DATA, small]. Early replies brought little engagement themselves. Their value was in relationships and visibility to the author, which this data cannot measure.
- In his 2026 list, he claims "replies beat posts when you're small. your post gets 50 views, a good reply on a viral post can get 50k". That is his claim, not verified here.
- His "pro tip: like posts from people < 1k followers / they'll see you in their notifs" (L413) is a related low-cost tactic.

Rules [GENERAL, consistent with the data]:
1. Reply to fresh posts (under ~1 hour old) from accounts 2–20× your size, where your reply can land near the top. Replies under huge viral posts get buried.
2. Each reply adds one thing: a number, a counter-example, a missing step, or a short story. Never "great post".
3. No links and no self-promo in replies.
4. A quote post must add a new judgment. Otherwise reply, or write your own original post on the topic. His quote-praise posts ("What a thread!") got 1 L.
5. When your reply does well, turn it into an original post the next day.

Reply templates [GENERAL]:
- **Add a number:** "Matches what I saw: [X out of Y] when I [did Z]."
- **Edge case:** "True for [A]. Breaks for [B], because [reason]."
- **Missing step:** "The step people skip: [step]. Without it, [consequence]."
- **Mini-story:** "Tried this last [month]. [Result with a number]. The surprise was [detail]."
- **Sharpen:** "Shorter version: [one-line reframe]."
- **Respectful counter:** "I'd push back on [point]: [evidence]. Curious if you've seen [case]."
- **Practical question (after adding value):** "[Your add]. How do you handle [specific sub-problem]?"

---

## 9. Fill-in templates by goal (26)

Each template is modeled on a real post (listed under it).

### Goal: saves (bookmarks)
1. **Expert's N rules**
   `a [credentialed person] who [proof] just laid out [N] rules for [topic]` + image of the rules
   Based on: YC partner, 8 rules (B3,611)
2. **How [famous thing] works**
   `"explain how [thing] works"` / `[honest reaction]` / `[authority] is right about this` / `[one-line prediction]` + video
   Based on: Shazam (B6,651)
3. **This is how [person] does [result]**
   `this is how [person] [achieves result]` + 1–2 images
   Based on: Nikita Bier (B2,881)
4. **I analyzed N**
   `I [did a big piece of research: N items]. [what you found], short list 👇` + 5–8 items, each with a number + `(bookmark this)`
   Based on: 6,000+ tweets (B2,332); 5,000+ accounts (B1,039)
5. **Credentials → resource list**
   `I've [credential 1], [credential 2], and [credential 3 with $/number]` / `The secret: [one claim]` / `The [N] [tools/steps] that [benefit] 👇`
   Based on: L3,434 / B3,161
6. **Masterclass + my notes**
   `[Who] just dropped a masterclass on [topic]. I've added my notes alongside.` + annotated image
   Based on: B610
7. **Then/now of a big account**
   `In [year], [person] didn't have [X]. Today [big number]. I studied [it], here are [N] tips:`
   Based on: Sahil Bloom (B528)
8. **Best-resource collection**
   `built the best resource for [task] / including the [N]+ best [examples] / [proof of quality] / start here: [link]`
   Based on: B610

### Goal: reach and likes
9. **Dollar-stakes meme**
   `* [Role] paid $[big] for [job] *` / `[setup]` / `[punchline] 👇` + image
   Based on: L6,918
10. **"me when" niche joke**
    `me when I [niche action]` + image
    Based on: L1,548
11. **AI/tool did something weird**
    `LOL!! [tool] randomly [surprising action] 🤯` / `([why it was unexpected])` + screenshot
    Based on: L3,748
12. **Small spend, absurd result**
    `handed [tool] [small $ / resource]` / `[minimal action]` / `[absurd outcome with number]` / `[honest reaction]` / `[broader take]`
    Based on: L1,612
13. **Reflective picture**
    `I keep coming back to this [picture/chart]` / `[why it matters to you]` + strong image
    Based on: L2,049

### Goal: follows and trust
14. **Struggle tally → win**
    `I had to face [N failures], [N setbacks], and [N years] to finally [win with $/number].` / `[why you're sharing now]` 👇
    Based on: L1,529
15. **Then/now timeline**
    `[years]: [emoji] • [mistakes ×4–5]` / `[years]: [emoji] • [what changed ×4–5]` / `[one-line lesson]`
    Based on: L413 / B223
16. **Consistency receipt**
    `I [did small action] every day for [N years]. It brought me: - [number] - [number] - [number]` / `[lesson]`
    Based on: L476
17. **Private talk with a known peer**
    `before [big decision], I had a long talk with [known person]` / `they almost convinced me [X]` / `their reasoning: - … - …` / `[what happened]`
    Based on: L680
18. **Absurd self-portrait (life)**
    `guys, I had no clue, but [doing N things] with [N life details] is so freaking hard`
    Based on: L772

### Goal: replies
19. **Open stage**
    `Are you [building/doing X]? / Congrats! / Here's your chance. / Share [your link + one-sentence pitch] 👇`
    Based on: L562
20. **News + poll the crowd**
    `it's done / [platform change in one line] / so tell me: / [specific yes/no question about their experience]`
    Based on: L629
21. **Hiring / "can anyone make this"**
    `if anyone reading this can create this, DM me / I'll [strong reward].` + example
    Based on: L963

### Goal: product case study (the product never leads)
22. **Newsjack demo**
    `[big news] / so I made [artifact] for them / (using [product] obviously 😅)` + the artifact
    Based on: Ferrari, L733
23. **Milestone + what worked**
    `[product] reached $[MRR] [emoji] / what worked for us: ✅ … ✅ … ✅ …`
    Based on: L343 / B195
24. **Customer win**
    `I am [emotion] right now / this [user] uses [product] and just reached [their number] / [humble credit]`
    Based on: L367 / B326
25. **Reader money/benefit first**
    `new way to [benefit with $]: / 👉 [action] on [product] / [how it works in 2–3 lines]`
    Based on: L364 / B466
26. **Expert access → free tool**
    `[expert] charges $[X] for [advice] / [exclusivity] / so we turned [it] into a free [tool] / it tells you: - … - … / [where to get it]`
    Based on: L257 / B521

---

## 10. Calendar, timing, and recycling

### 10.1 Volume
- His sampled months show up to ~25 originals in the last 4–10 days of a month, which is roughly 3–6 originals per day in recent years, plus replies. Early on he posted less.
- [GENERAL] For most people: 1–2 originals per day plus 3–10 quality replies is sustainable.

### 10.2 Weekly format mix [GENERAL, weighted by the data]

| Day | Format | Goal |
|---|---|---|
| Mon | Curated explainer + media | Saves |
| Tue | Personal number/story (win or failure) | Trust |
| Wed | Long list post (400–1,000 chars) with numbers | Saves |
| Thu | Meme / relatable niche joke / screenshot | Reach |
| Fri | Contrarian take or "pro tip" | Replies + reach |
| Sat | Life post (real detail) | Connection |
| Sun | Product case study in story form, or recycle a winner | Conversion |

Keep product-centered posts to at most ~1 in 7. His product posts get the lowest medians.

### 10.3 Timing [DATA, his account; adapt to your audience]

He posts from France. Median likes by hour, converted to UTC+8:
- **Best:** 17:00 (60 L), 18:00 (67), 20:00 (57.5). That is 09:00–12:00 UTC: European midday and the US East Coast morning.
- **Worst:** 01:00–06:00 UTC+8 (1–15 L).

Rule: post when your audience's core time zones are awake and at their desks. For a mostly US audience, that is US morning to lunch. Test 2–3 windows for 2 weeks each and compare medians.

### 10.4 Recycling winners [DATA]

| Original | Repost | Result |
|---|---|---|
| "I had to face 2 shutdowns, 1 bankruptcy…" 2023-11-28, L1,529 | 2024-02-22 | L246 (16%) |
| "These guys just dropped a masterclass…" 2025-02-18, L373 | 2025-08-29 | L94 (25%) |
| "influencer marketing is going to get very weird" 2026-05-26, L72 | 2026-05-30 | L75 (~100%) |
| Newsletter CTA "Sharing the playbook…" | 6× in 8 days | L0–7 each |

Rules:
- Recycle only proven winners, 2–6 months later, with a new first line or a new image.
- Expect 15–100% of the original. A big viral hit decays the most.
- Never recycle ads at a high frequency.

---

## 11. Post-publish review loop

[GENERAL, adapted to the data]

1. **At +1 hour:** check impressions and replies. Reply to every early reply. This keeps the conversation going.
2. **At +24 hours:** log impressions, likes, bookmarks, replies, and profile visits/follows in a sheet. Tag each post with: topic, hook type, length bucket, media yes/no, hour.
3. **Weekly:** compute medians per tag, not averages. Find your own versions of the tables in §2 and §4.
4. **Rewrite rule:** when a post is in your bottom 25% after 24 hours *and* the idea still seems good, rewrite the hook (see §12) and post it again 3–14 days later. Do not delete the original.
   - He claims a rework took one post from 7 to 380 L. That is his claim and was not verified in this data.
   - At large scale he reposts fast. At small scale, 30 minutes is not enough data; use 24 hours.
5. **Promote winners:** a post in your top 10% becomes:
   - a long post or thread expansion,
   - a recycled version in 2–6 months,
   - a pinned post, if it is evergreen.
6. **Ratios to watch:**
   - bookmarks / likes above ~0.5 means a save-worthy format (his curated posts run 0.8–2.7). Make more of it.
   - replies / likes above ~0.2 means a conversation topic. Do a follow-up.

---

## 12. Checklists and rewrites

### 12.1 Pre-post checklist
- [ ] Line 1 has a specific number, $ figure, name, or concrete object.
- [ ] Line 1 is a statement (or a question that filters a specific audience *and* gives them a reason to answer).
- [ ] One idea. A reader can say what it's about in 5 words.
- [ ] Proof: a number, screenshot, or personal experience. No claims you can't back.
- [ ] Format matches the goal (§2.2): long for saves, short + media for reach.
- [ ] Line breaks between ideas; lists use one bullet style.
- [ ] Media attached if at all possible, and it adds information.
- [ ] No link in the body unless the value already landed (otherwise put it in a reply).
- [ ] The product, if mentioned, is a case study or parenthetical, not the headline.
- [ ] 0–3 emoji, each doing a job.
- [ ] Posting time is in your audience's window.
- [ ] Honest: nothing fabricated, and no borrowed experience presented as yours.

### 12.2 Rewrite checklist (for a weak draft or a flop)
1. Move the most surprising number to the first 8 words.
2. Replace an adjective ("amazing", "must have", "really good") with a measurement.
3. Turn a question hook into a declaration of what you found.
4. Cut the first sentence when it is a warm-up.
5. Add the "why you" line (a credential, or what you did).
6. Add a list if there are 3+ points.
7. Add media, or replace a link with a screenshot.
8. End with a takeaway line, not "thoughts?".

### 12.3 Before → after examples (the "before" lines are his real low performers; the "after" lines are rewrites in his own winning patterns)

1. **Before:** "built in [link] / try it, it's really good" — L8
   **After** (pattern: newsjack demo, L733): "[Brand] just launched [X] / so I made their launch video in one prompt / (built with [tool] 😅)" + the video.
2. **Before:** "if you're serious about X, the SuperX extension is an absolute must have" — L2
   **After** (pattern: "I analyzed N", B2,332): "I tested [N] X tools for [N] days. Only [N] changed my numbers. Short list 👇 1. [tool]: [metric before → after]…"
3. **Before:** "How I got 15% new followers with a single tweet" — L3 (2021)
   **After** (pattern: hard number + method, L1,202): "1 post brought me [N] new followers in [N] hours. Here's exactly what it had: 1. … 2. … 3. …"
4. **Before:** "Does it help you prioritizing tasks or does it get you anxious?" — L0
   **After** (pattern: weird realization, L318): "i had a weird realization: my to-do list made me slower. I cut it from [N] items to [N]. Shipped [result] in [time]."
5. **Before:** "Never give up!" — L0
   **After** (pattern: struggle tally, L1,529): "[N] failed launches. [N] months with $0. Launch #[N] made $[X] in week one. What changed: [one thing]."
6. **Before:** "Sharing the playbook that turned years of failure into an $8m acquisition…" (CTA posted 6×) — L0–7
   **After** (pattern: expert access → free tool, B521): "[Expert] charges $[X]/hour for this playbook / so I wrote down the [N] steps for free / 1. … 2. … / full version in my newsletter (link in reply)."

---

## 13. Adapting for small accounts (< 1K followers)

1. **Expect a slow start.** He had a median of 1 like in 2020 and celebrated 1,000 followers with a post that got 3 likes. Judge your strategy by medians over 8–12 weeks, not single posts.
2. **Borrowed authority beats self-authority.** Without credentials, curated explainers ("this is how [famous person] does X", "[expert]'s N rules") are the most accessible top format. Add your own one-line take.
3. **Use process numbers when you have no money numbers.** Hours spent, items tested, error rates, the before/after of an experiment. The "number in line 1" effect does not need $ to work: posts with any digit in the first line had a median of 45 L vs 37 [DATA].
4. **Replies are distribution.** 1–2 high-quality replies a day on fresh mid-size posts (§8). Engage with people under 1K followers too; they notice.
5. **Long posts still work small.** Saves are a strong signal even with few likes.
6. **Don't over-recycle or delete.** Rewrite flops after 24 hours, not 30 minutes.
7. **Credentials compound.** Every real milestone (first user, first $, first 100 followers) is a future hook. Log them.
8. **Keep the product share low.** It is the weakest topic even for him, and it reads as an ad from an unknown account.

## 14. Adapting for niche or technical topics

1. **Translate to stakes.** Lead with the consequence ("cost $40 in 10 seconds", "3 of 722 failed") before the mechanism.
2. **Explainers are your edge.** "How [familiar thing] works" was his #1 post. Technical people can produce these better than anyone. Pick objects your audience already knows.
3. **In-group humor works.** Developer memes ("Regex… Stackoverflow", L578; "git push", L1,548) show that niche jokes reach far within a niche.
4. **Screenshots as proof.** Annotated outputs, error messages, and benchmarks are the technical version of "media with value".
5. **One jargon term per post, defined in passing.** [GENERAL]
6. **Numbers with units and denominators** ("11 of 40", not "27%"). His weak hook "15% new followers" vs his strong one "6,000+ tweets" points the same way. [DIRECTIONAL]
7. **Contrarian takes need evidence.** "Most of the growth advice is horse shit" got B334 because a list of reasons followed it.

---

## 15. Quick workflow when asked to write a post

1. Ask, or infer: the goal (saves / reach / follows / replies / product), the audience, and the proof available.
2. Pick a topic category (§3) and a format (§2.2).
3. Choose 2–3 hook patterns (§4) and write 3 first-line options.
4. Fill a template (§9). Add a number on every line where you can.
5. Run the pre-post checklist (§12.1).
6. Suggest media and a posting time (§6, §10.3).
7. Deliver the draft plus 2 alternative hooks. Never post on the user's behalf unless they explicitly ask.
8. Never invent numbers, experiences, or quotes. When proof is missing, mark a placeholder [NEED: number].
