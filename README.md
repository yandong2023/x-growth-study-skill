# X Post Writer

Two agent skills for X (Twitter). The main skill writes posts. The second skill studies an account's history and turns it into a playbook.

Neither skill publishes. Drafts go back to a person. Neither skill may invent statistics.

## X post writer (main skill)

`x-post-writer/SKILL.md` is the English writing guide (714 lines). `x-post-writer/SKILL.zh.md` is the Chinese guide (714 lines), with the same sections. The guide says its rules come from 1,044 original posts by @tibo_maker (about 212K followers, January 2020 through October 2026). That count is the one written in the guide. The study section below keeps a different case-study count.

It covers:

- Core rules
- Format and length data
- A topic map
- 36 hooks, taken from posts in the sample
- 20 teardowns of top posts
- Media
- Threads and long posts
- Replies and quote posts
- 26 fill-in templates
- A weekly calendar, with timing and recycling
- A post-publish review loop
- Checklists and rewrites
- Small accounts (under 1,000 followers)

The same files also have a short section on niche or technical topics, and a quick workflow for when the agent is asked to write a post.

## Install

Copy a skill folder into your agent's skills directory (Claude Code, Codex, or any agent that reads `SKILL.md`).

- Post writer: copy `x-post-writer/`. The agent loads `SKILL.md`. For the Chinese guide, point the agent at `x-post-writer/SKILL.zh.md`. If the agent only loads a file named `SKILL.md`, copy `SKILL.zh.md` to `SKILL.md` inside the installed folder.
- Account study: copy `x-account-growth-study/`. That skill needs X read tools: user lookup, user posts, and post search.

## X account growth study (second tool)

`x-account-growth-study/SKILL.md` tells an agent how to:

- pull a sample of an account's posts across its history, within API read limits
- analyze growth over time, post length, media, hooks (numbers, $ amounts, questions vs statements), topics, and posting hours, using medians
- state the sampling caveats honestly
- produce a report, a playbook, and a draft post built only on real numbers

### Methodology

Recent posts come from `get_users_posts`. History is searched in windows back to 2020: one window per month, or one window per quarter when the read budget is tight. Each search returns the newest posts in that window, so the sample is the end of the month or quarter, not every post from that period. Every call returns at most 25 posts.

Comparisons use medians, and each bucket reports its sample size `n`. Means are avoided because a few viral posts pull them up. The buckets are:

- length
- media versus text
- hooks (a number or a $ amount, and a question versus a statement)
- topic, from keyword tags
- posting hour

Three limits apply to every result:

- Month-end sampling. A window is the tail of that month or quarter, so the sample is not the full archive.
- Older posts lack bookmark data. Bookmark medians are missing or zero on old posts, so bookmark gaps overstate what older text actually earned.
- Keyword topic tags are rough. A post can be mislabeled, and a bucket with a tiny `n` is only a direction.

### Case study

One study of a founder account, sampled 2020-01 through 2026-10. The pull was 1,081 posts, of which 1,047 were originals, in about 52 API calls. The account had 212,617 followers at the time of the study. Figures below describe this sample only. 2026 runs through October, not a full year.

Median likes by year. 2025 dips to 64, below 85.5 in 2024 and 89 in 2026. Growth in this account is not a straight line. The source report gives a yearly `n` for 2020–2023. It gives 2024, 2025, and 2026 medians and does not give a separate `n` for those years.

| Year | Median likes | n |
| --- | --- | --- |
| 2020 | 1 | 114 |
| 2021 | 18 | 283 |
| 2022 | 39 | 200 |
| 2023 | 63 | 100 |
| 2024 | 85.5 | not in report |
| 2025 | 64 | not in report |
| 2026 | 89 | not in report |

Hooks, length, media, and format:

- A $ amount in the first line: median 133.5 likes and 49.5 bookmarks (n=46), versus 37 likes and 2 bookmarks for other posts (n=1,001).
- Length 281–600 characters: 90 likes and 38 bookmarks (n=74).
- Length over 600 characters: 120 likes and 68 bookmarks (n=8). Small sample. Directional only, not a rule.
- Length under 280 characters: 28–39 likes and 1–2 bookmarks.
- Posts with media: 60 likes and 17 bookmarks (n=135), versus 33 likes and 1 bookmark for text-only posts.
- Question openers: median 32 likes (n=94). Statement openers: median 40 likes (n=953). The gap is small and the samples are large, so this is directional only, not a rule, and it is not a small sample.
- Quote posts: median 22 likes. Original posts: median 43 likes.

Topics since 2024, median likes: product 62, other business 81, X-growth tactics 91, life 187 (n=7). Life is a small sample. Directional only, not a rule. Product posts are the lowest of these four.

The top posts are curated explainers. The Shazam explainer reached 8,219 likes and 6,651 bookmarks.

Reposts decay. One repeated opening fell from 1,529 likes to 246 likes.

The best hours in this sample were 17:00–20:00 Beijing time.

### Playbook

Six readings of the numbers above. They are not a promise for a different account. A line marked directional is not a rule.

1. Lead with a number. A $ amount in the first line had a median of 133.5 likes and 49.5 bookmarks (n=46), against 37 likes and 2 bookmarks (n=1,001).
2. Use long checklist posts when the goal is saves. Posts of 281–600 characters had 38 bookmarks (n=74), against 1–2 bookmarks under 280 characters. Posts over 600 characters had 68 bookmarks (n=8). That longer bucket is a small sample: directional only, not a rule that more length is always better.
3. Add an image. Posts with media had 60 likes and 17 bookmarks (n=135), against 33 likes and 1 bookmark for text.
4. Statement versus question is directional only, not a rule. Statements had a median of 40 likes (n=953), questions 32 (n=94). The samples are large and the gap is small.
5. Mention a product as a case study inside the post, not as the whole post. Since 2024, product posts had a median of 62 likes, below other business (81) and X-growth tactics (91). Life posts were at 187 likes, but n=7, so that comparison is a small sample and directional only, not a rule.
6. Expect growth to be slow, then to compound, and still to dip. The 2020 median was 1 like (n=114). Later years are much higher, and 2025 still fell to 64 before 2026 reached 89.

## License

[MIT](LICENSE) — Copyright 2026 yandong2023.

# 中文介绍

这个仓库有两份智能体技能。主技能用来写帖。第二份技能用来研究一个账号的历史，再写成打法。

两份技能都不会发帖。草稿交还给人。两份技能都不得编造统计。

## X 发帖写作（主技能）

`x-post-writer/SKILL.md` 是英文写作指南（714 行）。`x-post-writer/SKILL.zh.md` 是中文指南（714 行），章节相同。指南写明：规则来自 @tibo_maker 的 1,044 条原创帖（约 21.2 万粉，2020 年 1 月到 2026 年 10 月）。这是指南文件里写的样本量。下面的研究部分保留另一组案例数字。

它包括：

- 核心规则
- 格式和篇幅数据
- 选题地图
- 36 种开头，都来自样本里的帖子
- 20 条爆款拆解
- 配图
- 线程和长帖
- 回复和引用转发
- 26 个填空模板
- 一周日历，含发帖时间和旧帖再利用
- 发帖后的复盘流程
- 检查清单和改写
- 小号（粉丝不到 1,000）

同一份文件里还有一小节讲小众或技术话题，以及被要求写帖时的快速流程。

## 安装

把技能文件夹复制到智能体的技能目录（Claude Code、Codex，或其他会读取 `SKILL.md` 的智能体）。

- 发帖写作：复制 `x-post-writer/`。智能体加载的是 `SKILL.md`。要用中文指南，就让智能体读 `x-post-writer/SKILL.zh.md`。如果智能体只认名为 `SKILL.md` 的文件，就把安装目录里的 `SKILL.zh.md` 复制成 `SKILL.md`。
- 账号研究：复制 `x-account-growth-study/`。这份技能需要 X 的读取工具：用户查询、用户帖子、帖子搜索。

## X 账号增长研究（第二份工具）

`x-account-growth-study/SKILL.md` 让智能体做这些事：

- 在接口读取额度内，抽取该账号整个历史里的一批帖子
- 用中位数看增长、篇幅、图片、钩子（数字、金额、问句还是陈述句）、话题和发帖小时
- 把抽样的局限说清楚
- 交出一份报告、一份打法，以及一条只使用真实数字的草稿

### 方法

近期帖子用 `get_users_posts` 拉取。2020 年以来的历史按时间窗口搜索：通常每月一个窗口，要省调用次数时每季度一个窗口。每个窗口返回的是其中较新的帖，所以抽到的是月末或季末，不是这一段里的每一条。每次调用最多返回 25 条。

比较一律用中位数，并且每个分组都标出样本量 `n`。不用平均数，因为几条特别火的帖会把平均数拉高。分组包括：

- 篇幅
- 有没有媒体，对照纯文字
- 钩子（数字或金额，以及问句对照陈述句）
- 话题（关键词打标）
- 发帖小时

每条结论都带着三个局限：

- 月末抽样。窗口只覆盖该月或该季的末尾，不是全部存档。
- 老帖没有收藏数据。较早帖子的收藏数缺失或为零，所以收藏差距会把老帖的真实表现说得过低。
- 关键词话题标签很粗。帖子可能被标错；`n` 很小的分组只能看方向。

### 案例

这是对一个创始人账号的一次研究，样本时间为 2020-01 到 2026-10。一共抽到 1,081 条帖子，其中原创 1,047 条，大约用了 52 次接口调用。研究时该账号有 212,617 个粉丝。下面的数字只描述这一份样本。2026 年只到 10 月，不是完整的一年。

各年中位数赞见下表。2025 年掉到 64，低于 2024 年的 85.5，也低于 2026 年的 89。这个账号的增长不是一条直线。原始报告给出了 2020–2023 每年的 `n`。2024、2025、2026 只有中位数，没有单独的 `n`。

| 年份 | 中位数赞 | n |
| --- | --- | --- |
| 2020 | 1 | 114 |
| 2021 | 18 | 283 |
| 2022 | 39 | 200 |
| 2023 | 63 | 100 |
| 2024 | 85.5 | 报告未给 |
| 2025 | 64 | 报告未给 |
| 2026 | 89 | 报告未给 |

钩子、篇幅、媒体和形式：

- 第一行里有金额（$）：中位数 133.5 赞、49.5 收藏（n=46）；其余帖子 37 赞、2 收藏（n=1,001）。
- 281–600 个字符：90 赞、38 收藏（n=74）。
- 超过 600 个字符：120 赞、68 收藏（n=8）。小样本，只能看方向，不能当成规律。
- 不到 280 个字符：28–39 赞、1–2 收藏。
- 带媒体：60 赞、17 收藏（n=135）；纯文字 33 赞、1 收藏。
- 问句开头：中位数 32 赞（n=94）。陈述句开头：中位数 40 赞（n=953）。两边样本量都大，差距很小，所以只能看方向，不能当成规律，也不是小样本。
- 引用帖：中位数 22 赞。原创帖：中位数 43 赞。

2024 年以来的话题，中位数赞：产品 62，其他商业 81，X 增长技巧 91，生活 187（n=7）。生活是小样本，只能看方向，不能当成规律。四组里产品帖最低。

最靠前的帖是整理好的解读。其中 Shazam 原理解读拿到 8,219 赞和 6,651 收藏。

重复发会衰减。同一个开头再发一次，赞从 1,529 掉到 246。

这份样本里表现最好的时段是北京时间 17:00–20:00。

### 打法

下面六条是对上面这些数字的读法，换一个账号不能直接当成保证。标了「只能看方向」的，就不是规律。

1. 用一个数字开头。第一行带金额的帖，中位数是 133.5 赞、49.5 收藏（n=46），对照是 37 赞、2 收藏（n=1,001）。
2. 想要收藏，就发长清单。281–600 个字符的帖有 38 个收藏（n=74），不到 280 个字符的只有 1–2 个收藏。超过 600 个字符有 68 个收藏（n=8）。这一组是小样本，只能看方向，不能当成「越长越好」的规律。
3. 配一张图。带媒体的帖是 60 赞、17 收藏（n=135），纯文字是 33 赞、1 收藏。
4. 陈述句对照问句，只能看方向，不能当成规律。陈述句中位数 40 赞（n=953），问句 32 赞（n=94）。两边样本量都大，差距很小。
5. 产品只当作帖子里的案例，不要整条帖都在讲产品。2024 年以来，产品帖中位数 62 赞，低于其他商业（81）和 X 增长技巧（91）。生活帖是 187 赞，但 n=7，所以这组对照是小样本，只能看方向，不能当成「生活话题一定赢」的规律。
6. 增长先很慢，之后才会一年年叠上去，中间仍会回落。2020 年中位数是 1 个赞（n=114）。后来的年份高很多，但 2025 年仍掉到 64，2026 年才到 89。

## 许可

[MIT](LICENSE) — 版权 2026 yandong2023。
