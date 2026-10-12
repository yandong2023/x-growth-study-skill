---
name: X post writer（中文版）
description: 撰写、改写、审阅能带来增长的 X（Twitter）帖子、长帖、线程、回复和引用转发。内容包括选题、30 多个附真实案例的开头写法、模板、排版、配图、发帖时间、旧帖再利用，以及发帖后的复盘流程。每条规则都来自对一个 21 万粉创始人账号（@tibo_maker，2020–2026）1,044 条原创帖的研究。写任何帖子、安排本周发什么、或者某条帖子表现不好时使用。
---

# X 发帖写作指南

这是一份实用的 X 写作指南，每条规则都有同一个对标账号的真实帖子作依据。案例原文保留英文，附点赞（L）、收藏（B）和链接。

---

## 0. 先读这里：证据和它的局限

**来源。** @tibo_maker（Tibo Louis-Lucas）是靠自筹资金起家的 SaaS 创始人。他做了 Tweet Hunter 和 Taplio，2022 年卖给了 Lempire，现在同时经营好几个 SaaS 产品。2026 年 10 月账号约有 21.2 万粉。

**样本。** 通过 X API 抓取的 1,044 条原创帖（不含回复和转推），时间从 2020 年 1 月到 2026 年 10 月。
- 2020–2022 年：几乎每个月取最后约 25 条。
- 2023 年起：每季度取一个月。
- 样本最后约两周基本是全量。

这是抽样，不是全部历史。他一共发过 4.9 万多条推文。

**指标。** 全文都用中位数，因为平均数会被爆款带偏。约 2023 年以前平台没有记录收藏数，所以收藏数的对比主要反映 2023–2026 年的帖子。

**本指南用的标记：**
- **[数据]**：从样本算出来的结论，附 n（帖子数量）。
- **[方向性]**：样本小（大约 n < 15），只能当作参考。
- **[通用]**：常规做法，这份数据不能证明。请自己判断。

**这份数据回答不了的问题：**
- 线程。很多帖子缺对话 ID，数据里没有可靠的线程结构。
- 回复。唯一的回复数据是 2021 年 6 月的 25 条样本。
- 删掉的帖子，以及粉丝数随时间的变化。
- 图片内容。数据只显示有没有附媒体，看不到图里是什么。

**增长背景**（来自样本中他自己的帖子和公开采访）：
- 2020 年：每条帖子点赞中位数 1（n=114）。2020-11-22 他发了 "Reached 1000 followers today 🔥🔥"（L3）。x.com/tibo_maker/status/1330592109762637826
- 2021 年 6 月："How I grew from 0 to 4k followers by getting inspiration from the best."（L92）。x.com/tibo_maker/status/1409860346320355334
- 每年的点赞中位数：2021 年 18，2022 年 39，2023 年 63，2024 年 85.5，2025 年 64，2026 年 89。
- 2024 年 11 月："I posted every day for 4 years. It brought me: 130k+ 𝕏 followers … a $8m exit … $100k+ MRR"（L476）。x.com/tibo_maker/status/1862155900297097481
- 采访：Tweet Hunter 2021 年 5 月有了第一个付费用户。2021 年 9 月一次网红合作发布让 MRR 从 3K 涨到 2 万美元。2022 年以 200 万美元首付加业绩对赌卖给 Lempire。

**第零条教训。** 第一年看起来什么都没有：点赞中位数只有 1。不要用前 3 个月的结果评判一个策略。

---

## 1. 核心规则（一屏看完）

1. **第一行放一个硬数字。** 第一行带 $ 金额：中位数 133.5 赞 / 49.5 收藏（n=46）。其他所有帖子：37 赞 / 2 收藏（n=1,001）。[数据]
2. **陈述，不要提问。** 第一行是问句：中位数 32 赞（n=94）。陈述句：40 赞（n=953）。[数据]
3. **想要收藏就写长。** 281–600 字符：90 赞 / 38 收藏。280 字符以下：28–39 赞 / 1–2 收藏。[数据]
4. **配媒体。** 带媒体：60 赞 / 17 收藏（n=135）。纯文字：33 赞 / 1 收藏（n=912）。[数据]
5. **产品放进故事里，别写成广告。** 2024 年以来：提产品的帖 62 赞，非产品的商业帖 81 赞，生活帖 187 赞 [方向性，n=7]。
6. **做整理和解读。** 他排第一的帖子是一条 "X 是怎么运作的" 整理解读：8,219 赞 / 6,651 收藏。[数据]
7. **多写原创，少用引用转发。** 引用转发：22 赞。原创：43 赞。[数据]
8. **只贴链接的帖必死。** "built in [link] try it, it's really good"：8 赞。[数据，例子见 §3.6]
9. **重发爆款，但第二次的预期要放低。** 有一次重发从 1,529 赞掉到 246 赞。[数据，§10]
10. **每天发，坚持几年。** [数据：见上面的年度曲线]

---

## 2. 格式与长度

### 2.1 长度表 [数据]

全部帖子：

| 字符数 | n | 点赞中位数 | 收藏中位数 |
|---|---|---|---|
| < 80 | 219 | 28 | 1 |
| 80–280 | 746 | 39 | 2 |
| 281–600 | 74 | 90 | 38 |
| > 600 | 8 | 120 | 68 [方向性] |

只看 2024 年以后（去掉早期小号阶段）：

| 字符数 | n | 点赞中位数 | 收藏中位数 |
|---|---|---|---|
| < 80 | 50 | 72 | 9.5 |
| 80–280 | 225 | 72 | 14 |
| 281–600 | 67 | 96 | 38（全年份数值） |
| > 600 | 8 | 120 | 68 [方向性] |

**怎么读这张表。**
- 账号成熟以后，短帖和中等长度帖子的点赞差不多。
- 长帖在收藏上明显胜出，而收藏说明这条帖子值得留着。
- 短帖上限更高，下限也更低。他点赞最高的帖子里有好几条不到 110 字符（Meta 程序员梗图 103，"git push" 梗图 60，"I keep coming back to this picture" 107）。但大多数短帖都没水花。

### 2.2 按目标选格式

| 目标 | 格式 | 依据 |
|---|---|---|
| 收藏 / 建立权威 | 281–1,000+ 字符的清单或指南，或附笔记的整理资源 | "posted 6,000+ tweets since 2020"（1,079 字符）：1,202 赞 / 2,332 收藏 |
| 纯曝光 / 点赞 | 120 字符以内，配一张有共鸣的图、梗图或视频片段 | "* Meta paying $500k/y for senior dev *"（103 字符，带媒体）：6,918 赞 / 380 收藏 |
| 信任 / 涨粉 | 带数字的个人成功或失败故事 | "I had to face 2 shutdowns, 1 bankruptcy…"：1,529 赞 / 998 收藏 |
| 回复 / 讨论 | 直接邀请大家分享，并给出回复的理由 | "Are you building a startup? … Share the link and your one sentence pitch! 👇"：562 赞 / 409 收藏 |

### 2.3 换行和排版 [数据 + 通用]

- 有 3 个及以上换行的帖子（2024 年以后）：中位数 88 赞（n=227）。换行更少的：63 赞（n=123）。[数据]
- 一行一个意思，段落之间空一行。他的长帖读起来是这样：
  ```
  posted 6,000+ tweets since 2020
  built an X growth tool and sold it for $10m

  so I pulled my own data to see what actually works on X right now

  short list 👇

  1. replies beat posts when you're small. ...
  ```
- 列表。带编号或项目符号列表的帖子：55 赞 / 8 收藏，没有列表的是 37 赞 / 2 收藏。[数据]
- 他用过的列表符号：`1.`、`•`、`-`、`→`、`✅`、`🤖`。一条帖子只用一种。
- 全小写、随意的语气（2024 年以后）：81 赞（n=155），正常大小写是 73 赞。基本持平，按自己的风格选。[数据]

### 2.4 Emoji [数据]

- 2024 年以后：带至少一个 emoji 的帖子中位数 68 赞（n=169），不带的 88 赞（n=181）。平均来看 emoji 没有帮助。
- 他把 emoji 当**路标**用，不当装饰：
  - 👇 指向下面的清单或链接
  - 🤯 标出让人惊讶的数字
  - ✨ / 🚨 当发布公告的括号（"✨ Taplio X is OUT ✨"，347 赞）
  - 😅 冲淡一句自我推销
- 规则：最多 1–3 个，每个都要有作用。

### 2.5 链接 [数据]

- 2024 年以后：正文带链接的帖子中位数 59 赞（n=55），不带的 82 赞（n=295）。
- 他几乎零互动的帖子大多是后续贴链接的帖：
  - "more wisdom: [link] - delivered every week"：5 赞
  - "built in [link] try it, it's really good"：8 赞和 13 赞
  - "if you're serious about X, the SuperX extension is an absolute must have"：2 赞
- 规则：不点链接也要能拿到价值。链接放在回复里，或者等价值讲完再放。

---

## 3. 选题地图

样本中各类占比（按关键词分类，只是大概）：商业观点 / 其他 70%，产品 16%，X 增长技巧 12%，生活 2%。2024 年以来点赞中位数：生活 187 [方向性，n=7]，技巧 91，商业 81，产品 62。

### 3.1 整理解读，以及"某个厉害的人说了 X" —— 收藏最高

他把别人的知识打包，加一句自己的看法，再配上媒体。

- "explain how Shazam works" / I had no idea / Karpathy is so right about this / custom explainer videos will change education。**8,219 赞 / 6,651 收藏**。x.com/tibo_maker/status/2105980242321924284
- "a YC partner who closed millions in founder-led sales just laid out her 8 rules for cold email"。**1,342 赞 / 3,611 收藏**。x.com/tibo_maker/status/2103779177191063879
- "this is how Nikita Bier builds viral apps"。**1,152 赞 / 2,881 收藏**（2 个媒体）。x.com/tibo_maker/status/2106301320848171339
- "Here's Sam Altman, Founder of OpenAI, on cold outreach: Very practical advice indeed."。**1,055 赞 / 1,878 收藏**。x.com/tibo_maker/status/1829163380717781434
- "These guys just dropped a masterclass on how (and what) to focus as a startup founders. Tons of insights here. I've added my notes alongside."。**373 赞 / 610 收藏**。x.com/tibo_maker/status/1891808592619290706
- "In 2018, Sahil Bloom didn't have a Twitter account. Today he has almost 700K followers. I studied his growth… 12 growth tips"。**376 赞 / 528 收藏**。x.com/tibo_maker/status/1573626553002590208
- "the leaked MrBeast production doc has a great lesson for founders"。**319 赞 / 294 收藏**。x.com/tibo_maker/status/2093269905000804527

套路：一个知名人物或事物 + 一个具体承诺（几条规则，或"它是怎么运作的"）+ 媒体 + 一句简短的个人看法。

### 3.2 带数字的个人成绩

- "I've sold 2 startups, cofounded 4, and scaled one to $1 million ARR / The secret: launching in 30 days / The 17 tools that will get you to launch FAST 👇"。**3,434 赞 / 3,161 收藏**。x.com/tibo_maker/status/1540337710371688448
- "I had to face 2 shutdowns, 1 bankruptcy, and 7 winding years of hustle to finally have my first win - a $10M acquisition."。**1,529 赞 / 998 收藏**。x.com/tibo_maker/status/1729497635487121541
- "before selling Tweet Hunter for $10m, I had a long talk with @levelsio / he almost convinced me not to do it"。**680 赞 / 321 收藏**。x.com/tibo_maker/status/2093238410680946841
- "I posted every day for 4 years. It brought me: 130k+ 𝕏 followers…"。**476 赞 / 124 收藏**。
- "THIS IS IT 🤯 In 1 year, we went from 0 to $1m ARR"。**463 赞 / 145 收藏**。x.com/tibo_maker/status/1529441166990749697
- "3 years ago, I acquired Typeframes for $50,000 / and turned it into an asset generating $500,000 per month"。**445 赞 / 231 收藏**。x.com/tibo_maker/status/2104526662910025988
- "2015-2019: 🤦‍♂️ Built 2 'next Facebook' startups… 2021-2025: 🎯 Built 30+ products"。**413 赞 / 223 收藏**。x.com/tibo_maker/status/1926933888347095400
- "I started the year shipping 1 product per week / Quantity led to quality / $20k MRR!!!"。**357 赞 / 65 收藏**。x.com/tibo_maker/status/1461368157818568705

套路：具体的里程碑（次数、金额、年数），成功之前的挣扎，再加一条别人也能用的教训。

### 3.3 生活、共鸣和幽默 —— 单条点赞最高

- "* Meta paying $500k/y for senior dev * / PM: page load is slow / Senior Dev fix 👇" + 媒体。**6,918 赞**。x.com/tibo_maker/status/1829131328404570522
- "LOL!! Claude (via Cursor) randomly tried to update the model of my feature from OpenAI to Claude 🤯"。**3,748 赞**。x.com/tibo_maker/status/1895408283818881505
- "I keep coming back to this picture / it puts a lot of things into perspective for me" + 图。**2,049 赞 / 521 收藏**。x.com/tibo_maker/status/2108490225982775619
- "me when I write "git push" to Claude" + 媒体。**1,548 赞**。x.com/tibo_maker/status/2104907857065881941
- "guys, I had no clue, but managing 7 SaaS with 2 kids while playing WoW 8 hours per day is so freaking hard"。**772 赞**。x.com/tibo_maker/status/2104141537919615123
- "every week, I ship more than the full year I spent as a CTO… and still have time to take walks with my wife / I love this life"。**354 赞**。x.com/tibo_maker/status/1991846742468272386
- "✨ new French tax ✨ … net in pocket is 36% of my profit"。**576 赞**。x.com/tibo_maker/status/1991822187427209524
- "I am a developer for 12 years. I still pray for the Regex I want to be on Stackoverflow."。**578 赞**。x.com/tibo_maker/status/1442041229131194370

套路：只有圈内人懂的笑话，或者真实生活里的一个瞬间，带一个具体细节（7 个 SaaS、2 个孩子、每天 8 小时魔兽）。

### 3.4 技巧与观点

- "posted 6,000+ tweets since 2020… short list 👇 1. replies beat posts…"。**1,202 赞 / 2,332 收藏**。
- "AI isn't killing jobs. It's killing employment as we know it. My prediction: • The 9-5 will die…"。**793 赞 / 301 收藏**。x.com/tibo_maker/status/1894016656319635956
- "pro tip: like posts from people < 1k followers / they'll see you in their notifs"。**413 赞**。x.com/tibo_maker/status/1961009573151506837
- "Most founders you look up to aren't particularly special... They were just too stupid to quit."。**324 赞**。x.com/tibo_maker/status/1792861397937733689
- "Most of the startup growth advice is horse shit."。**141 赞 / 334 收藏**。x.com/tibo_maker/status/1763199702986543216
- "i had a weird realization recently… and then google p-max beat all of them"。**318 赞 / 345 收藏**。x.com/tibo_maker/status/2058519964491952169
- "My full-time job at @TweetHunterIO is to discover the best strategies… analyzed 5,000+ accounts… blueprint to go from 100-10k FANS"。**543 赞 / 1,039 收藏**。x.com/tibo_maker/status/1605884368521666563

### 3.5 效果好的产品帖（产品藏在故事里）

- "Ferrari launched their first electric car / so I made a launch video for them / (using Revid obviously 😅)"。**733 赞**。x.com/tibo_maker/status/2059499312472604877（蹭新闻 + 演示）
- "if anyone reading this can create this, DM me / I'll hire you instantly. / I need to do more on Revid"。**963 赞 / 801 收藏**。
- "I am crying right now 🥲 / this guy uses 3 of my products and just reached 11k MRR"。**367 赞 / 326 收藏**。x.com/tibo_maker/status/2108841747941925192（用户成功案例）
- "Outrank reached $120,000 MRR 😳 / what worked for us: ✅…"。**343 赞 / 195 收藏**。x.com/tibo_maker/status/1960998387076960691（里程碑 + 经验）
- "I just can't believe that this software that was making < $1000/m when I bought it, has now reached $200,000 ARR 🤯"。**340 赞**。x.com/tibo_maker/status/1828029214345347431
- "new way to make an extra $50k+/year: 👉 sell backlinks on Outrank"。**364 赞 / 466 收藏**。x.com/tibo_maker/status/2092166071654445257（给读者的赚钱好处）
- "I hired 7 AI agents this month & they've taken over my SaaS 😱 here's my actual org chart"。**367 赞 / 444 收藏**。x.com/tibo_maker/status/2059930221680189744

套路：先讲读者能得到什么、一个数字、一个故事或一条新闻，产品名放后面或放在括号里。

### 3.6 失败的产品帖（反面教材）

- "built in [link] / try it, it's really good"。**8 赞**。x.com/tibo_maker/status/2106686499865399586（重发一次 13 赞）
- "built by [link] which goes much further than just using Opus 5.5"。**6 赞**。
- "if you're serious about X, the SuperX extension is an absolute must have"。**2 赞**。x.com/tibo_maker/status/2109352693651427600
- "if you guys want to learn more about weird niche stuff, i've just created a new YT channel for this: [link]"。**2 赞**。
- "I WILL BUY THIS 50,000 CAR 🤩 nano-banana-pro in Revid is seriously impressive"。**4 赞**。
- "Sharing the playbook that turned years of failure into an $8m acquisition…"（Newsletter 推广，8 天发了 6 次）。**每次 0–7 赞**。开头的数字再强，只要是反复出现的广告就没人看。

它们的共同点：一个链接加一个形容词（"really good"、"must have"），读者不点进去什么也学不到。

---

## 4. 开头库（36 种，全部来自他的帖子）

格式：**写法** —— 真实的第一行 —— 数据 —— 什么时候用。

### A. 数字和金额开头
1. **叠战绩** —— "I've sold 2 startups, cofounded 4, and scaled one to $1 million ARR" —— 3,434 赞 / 3,161 收藏。手里有真实成绩时，用来引出清单或指南。
2. **失败次数 → 成功** —— "I had to face 2 shutdowns, 1 bankruptcy, and 7 winding years of hustle to finally have my first win - a $10M acquisition." —— 1,529 赞 / 998 收藏。用于讲创业起点的故事。
3. **给别人的时间标价** —— "Nikita Bier charges $500 a minute for advice" —— 257 赞 / 521 收藏。让免费内容显得有价值。
4. **用金额铺垫笑点** —— "* Meta paying $500k/y for senior dev *" —— 6,918 赞。数字越大，笑点越响。
5. **花小钱，结果离谱** —— "handed my OpenClaw an API key with $40 in credits… burned through everything in 10 seconds" —— 1,612 赞。适合讲 AI 和工具的使用体验。
6. **低价买入，高位增长** —— "3 years ago, I acquired Typeframes for $50,000 / and turned it into an asset generating $500,000 per month" —— 445 赞 / 231 收藏。
7. **收入的前后对比** —— "this software that was making < $1000/m when I bought it, has now reached $200,000 ARR 🤯" —— 340 赞。
8. **里程碑 + "什么起了作用"** —— "Outrank reached $120,000 MRR 😳 / what worked for us:" —— 343 赞 / 195 收藏。
9. **给读者的赚钱好处** —— "new way to make an extra $50k+/year:" —— 364 赞 / 466 收藏。
10. **把账算出来** —— "✨ new French tax ✨ … 67% * 55% * 97% = 36%" —— 576 赞。把计算过程摆出来。
11. **对名人的推算** —— "is it safe to assume @levelsio has $36m invested? 🤯" —— 410 赞 / 250 收藏。少数有效的问句开头之一，因为它带了数字和名人。
12. **用数量建立可信度** —— "posted 6,000+ tweets since 2020" —— 1,202 赞 / 2,332 收藏。
13. **调研量** —— "I've done all the research and analyzed 5,000+ accounts for you." —— 543 赞 / 1,039 收藏。
14. **坚持的年数** —— "I posted every day for 4 years." —— 476 赞。

### B. 整理和解读开头
15. **引号里的问题 + "X 是怎么运作的"** —— ""explain how Shazam works"" —— 8,219 赞 / 6,651 收藏。
16. **有背书的人 + N 条规则** —— "a YC partner who closed millions in founder-led sales just laid out her 8 rules for cold email" —— 1,342 赞 / 3,611 收藏。
17. **"这就是 [名人] 怎么做 X 的"** —— "this is how Nikita Bier builds viral apps" —— 1,152 赞 / 2,881 收藏。
18. **"这是 [名人] 谈 [话题]："** —— "Here's Sam Altman, Founder of OpenAI, on cold outreach:" —— 1,055 赞 / 1,878 收藏。
19. **大师课 + 我的笔记** —— "These guys just dropped a masterclass on… I've added my notes alongside." —— 373 赞 / 610 收藏。
20. **大号的过去与现在** —— "In 2018, Sahil Bloom didn't have a Twitter account. Today he has almost 700K followers." —— 376 赞 / 528 收藏。
21. **泄露或内部文件** —— "the leaked MrBeast production doc has a great lesson for founders" —— 319 赞 / 294 收藏。
22. **"最佳资源"合集** —— "built the best resource for your own Motion Graphics video / including the 50+ best videos" —— 352 赞 / 610 收藏。

### C. 故事和自白开头
23. **情绪开场** —— "I am crying right now 🥲" —— 367 赞 / 326 收藏。
24. **奇怪的领悟** —— "i had a weird realization recently" —— 318 赞 / 345 收藏。
25. **和知名同行的私下谈话** —— "before selling Tweet Hunter for $10m, I had a long talk with @levelsio" —— 680 赞 / 321 收藏。
26. **觉得自己落后 → 一个小胜利** —— "you know this feeling when you see everyone doing amazing things, and it just drains all your energy…" —— 478 赞。
27. **一张让人换个角度看的图** —— "I keep coming back to this picture" —— 2,049 赞 / 521 收藏。
28. **荒诞的自画像** —— "managing 7 SaaS with 2 kids while playing WoW 8 hours per day is so freaking hard" —— 772 赞。

### D. 反常识和断言开头
29. **重新定义** —— "AI isn't killing jobs. / It's killing employment as we know it." —— 793 赞 / 301 收藏。
30. **"大多数 X 都……"** —— "Most founders you look up to aren't particularly special..." —— 324 赞。"Most of the startup growth advice is horse shit." —— 141 赞 / 334 收藏。
31. **"大家都把这个观点理解错了"**（"People get this take wrong"）—— 433 赞。x.com/tibo_maker/status/1827615427779838001
32. **"pro tip:"** + 一个反直觉的小技巧 —— "pro tip: like posts from people < 1k followers" —— 413 赞。
33. **过去 vs 现在的时间线** —— "2015-2019: 🤦‍♂️ … 2021-2025: 🎯" —— 413 赞 / 223 收藏。

### E. 互动开头
34. **开放舞台** —— "Are you building a startup? / Congrats! 👏 / Here's your chance. / Share the link and your one sentence pitch! 👇" —— 562 赞 / 409 收藏。少数成功的问句开头之一：问题在筛选人群，而且请求很具体。
35. **新闻 + 问大家** —— "it's done / X removed the ability to reply through the API / so tell me: are you seeing a huge reduction in AI replies today?" —— 629 赞。
36. **招人帖顺便展示作品** —— "if anyone reading this can create this, DM me / I'll hire you instantly." —— 963 赞 / 801 收藏。

### F. 反面教材（真实的低表现帖）

| 开头 | 点赞 | 为什么失败 |
|---|---|---|
| "So where are you now? [link]"（2020） | 0 | 问题含糊，没有上下文 |
| "Does it help you prioritizing tasks or does it get you anxious?"（2020） | 0 | 问题和读者无关痛痒 |
| "Never give up! [link]"（2020） | 0 | 空泛的鸡汤 |
| "Don't wait for inspiration to come to you! act on your ideas now"（2020） | 1 | 套话，没有证据 |
| "How to start your product in 5 steps:"（2020-12） | 1 | 承诺了清单，但当时还没有背书 |
| "How I got 15% new followers with a single tweet"（2021-02） | 3 | 基数很小的百分比显得没分量 |
| "What a thread!" / "Best thread I read in a very long time [link]" | 1 | 引用转发只夸不加内容 |
| "built in [link] / try it, it's really good"（2026） | 8 | 只贴产品链接 |
| "more wisdom: [link] - delivered every week" | 5 | Newsletter 广告 |

注意前几行的时间。同样的 "How to" 格式，2020 年只拿到 1 赞；到 2021 年年中，"How I grew" 那一版拿到 92 赞。证据和受众规模会改变一种开头的效果。

---

## 5. 他的爆款拆解

### T1. "explain how Shazam works" —— 8,219 赞 / 6,651 收藏（171 字符，带媒体）
```
"explain how Shazam works"          ← 引号里的提问：好奇心 + 人人都知道 Shazam

I had no idea                        ← 真实反应，4 个词，放低姿态

Karpathy is so right about this      ← 借权威，加入一场正在进行的讨论
custom explainer videos will change education   ← 观点：一句话预测
[link] [video]                       ← 价值在媒体里
```
为什么有效：人人都认识的东西、好奇心、权威名字、简短观点，再加一段值得收藏的视频。观点不是他自己提出的，他做的是整理。

### T2. "* Meta paying $500k/y for senior dev *" —— 6,918 赞（103 字符，带媒体）
```
* Meta paying $500k/y for senior dev *   ← 场景说明 + 大金额
PM: page load is slow                    ← 有共鸣的铺垫
Senior Dev fix 👇                        ← 指向笑点所在的媒体
```
为什么有效：梗图格式、程序员圈内笑话，金额抬高了反差。能带来曝光，但没人收藏（380 收藏）。

### T3. "LOL!! Claude (via Cursor) randomly tried to update the model…" —— 3,748 赞
结构：一个反应词 → AI 工具干的一件具体又好笑的事 → 括号里说明这不是他让它做的 → 截图。为什么有效：话题正热（AI 编程工具），截图就是证据，读者愿意转发。

### T4. "I've sold 2 startups, cofounded 4, and scaled one to $1 million ARR" —— 3,434 赞 / 3,161 收藏（151 字符）
```
I've sold 2 startups, cofounded 4, and scaled one to $1 million ARR   ← 3 项叠起来的战绩
The secret: launching in 30 days                                      ← 一个论点
The 17 tools that will get you to launch FAST 👇                      ← 带数字的资源承诺
```
为什么有效：战绩让清单可信，"17 个工具"值得收藏，👇 引出线程或清单。

### T5. "I keep coming back to this picture" —— 2,049 赞 / 521 收藏
两行短句 + 一张图。为什么有效：带情绪、偏反思的说法让人代入自己的理解，所有分量都在图上。只有图真的很强时才管用。

### T6. "handed my OpenClaw an API key with $40 in credits" —— 1,612 赞（202 字符，纯文字）
```
handed my OpenClaw an API key with $40 in credits   ← 小金额 + 动作
asked a single question                             ← 极少的输入
agent burned through everything in 10 seconds       ← 离谱的结果，第二个数字
still don't know what it actually did               ← 坦白自己也没搞懂
imagine giving real money to those things           ← 观点：更大的警示
```
为什么有效：一个带两个数字的微型故事，每行一个节奏点，最后落到一个观点。

### T7. "me when I write "git push" to Claude" —— 1,548 赞
"me when" 格式的梗图，加一个圈内笑话。纯曝光。

### T8. "I had to face 2 shutdowns, 1 bankruptcy…" —— 1,529 赞 / 998 收藏（250 字符）
```
I had to face 2 shutdowns, 1 bankruptcy, and 7 winding years of hustle   ← 失败清单
to finally have my first win - a $10M acquisition.                       ← 大金额回报
This is the first time I'm sharing the full story here.                  ← 独家感
A thread on the reality of startup success 👇🏻                           ← 线程承诺
```
为什么有效：一个袒露脆弱的故事，失败和 1,000 万美元形成强烈反差。

### T9. "a YC partner … 8 rules for cold email" —— 1,342 赞 / 3,611 收藏（118 字符）
权威 + 证据（"closed millions"）+ 规则数量 + 媒体。收藏是点赞的 2.7 倍，是数据里最强的"收藏磁铁"格式。

### T10. "posted 6,000+ tweets since 2020" —— 1,202 赞 / 2,332 收藏（1,079 字符）
```
posted 6,000+ tweets since 2020                  ← 用数量建立可信度
built an X growth tool and sold it for $10m      ← 金额战绩
so I pulled my own data to see what actually works on X right now   ← 方法
short list 👇
1.–8. 每一条：规则 + 他自己的数字               ← 每条都有证据
(bookmark this post btw)                         ← 帖子中间直接提醒收藏
on top of that, one core rule: ...               ← 总结规则
this is a hard and long journey ...              ← 诚实的收尾
```
为什么有效：战绩 + 数据 + 编号清单 + 每条一个数字 + 提醒收藏 + 诚实的结尾。

### T11. "this is how Nikita Bier builds viral apps" —— 1,152 赞 / 2,881 收藏（65 字符，2 个媒体）
一行短句、一个知名操盘手、一个"怎么做"的承诺，价值都在图里。收藏是点赞的 2.5 倍。

### T12. "Here's Sam Altman, Founder of OpenAI, on cold outreach:" —— 1,055 赞 / 1,878 收藏
名字 + 头衔 + 话题 + 冒号，接一句简短的看法（"Very practical advice indeed. Even if you are a tech genius like him, you NEED reliable lead gen"），然后是视频片段。

### T13. "if anyone reading this can create this, DM me" —— 963 赞 / 801 收藏
招人帖是高姿态的社交证明（"I'll hire you instantly"），同时展示了作品，最后才提产品（"I need to do more on Revid"）。

### T14. "AI isn't killing jobs." —— 793 赞 / 301 收藏（381 字符）
```
AI isn't killing jobs.
It's killing employment as we know it.     ← 两行完成重新定义
My prediction:
• The 9-5 will die
• Big corps will shrink
• Solo creators will thrive
• Everyone becomes an entrepreneur
• The middle class splits into 2 groups:（下面还有子项）
The greatest wealth transfer of our time isn't crypto or stocks.
It's the ability to use AI effectively.   ← 可以被引用的结尾，和开头呼应
```

### T15. "guys, I had no clue, but managing 7 SaaS with 2 kids while playing WoW 8 hours per day…" —— 772 赞
带 3 个具体数字的自嘲。看起来是玩笑，其实是低调炫耀。属于生活类内容。

### T16. "Ferrari launched their first electric car / so I made a launch video for them" —— 733 赞
蹭新闻：大新闻 → 我用它做了个东西 → 括号里提产品，配 😅。产品是工具，不是主角。

### T17. "My full-time job at @TweetHunterIO is to discover the best strategies…" —— 543 赞 / 1,039 收藏
工作带来的权威 + 调研量（5,000+ 个账号）+ "万无一失的蓝图"这个承诺，配一个具体的区间（100–1 万）。收藏是点赞的 2 倍。

### T18. "Hey, all FAANG smart tech people…" —— 670 赞 / 1,001 收藏
点名一个具体人群 → 重新定义（"have you tried Indie Making?"）→ 带金额的打法承诺（"$1M/year one-person business"）。

### T19. "Nikita Bier charges $500 a minute for advice" —— 257 赞 / 521 收藏（487 字符）
价格锚点 → "only takes calls with VC-backed founders"（稀缺）→ "so we turned his whole … playbook into a free, open-source AI skill"（免费价值）→ 4 条你能得到什么 → 行动号召。一次产品发布，包装成了"免费接触专家"。

### T20. "Are you building a startup? Share the link…" —— 562 赞 / 409 收藏
筛选人群的问题 + 祝贺 + 具体请求。有效是因为读者回复就能免费曝光。

### 爆款的共同点
- 第一行前面就有具体的名词、人名或数字（这 20 条几乎都是；这是肉眼判断，没有计算）。
- 曝光最高的帖子几乎都带媒体。纯文字的爆款都带数字或清单。
- 整理别人的内容时，旁边加一句自己的看法。
- 这 20 条里最多 3 条提到产品，而且没有一条把产品放在第一行。

---

## 6. 配图指南

[数据]
- 带媒体：中位数 60 赞 / 17 收藏。纯文字：33 赞 / 1 收藏。
- 点赞前 10 的帖子里 6 条带媒体，收藏前 5 里 3 条带媒体。
- 媒体类型本身没有抓到，下面的分类是从帖子文字推断的。

从他的爆款推断出的媒体类型：

| 类型 | 例子 | 数据 |
|---|---|---|
| 专家的解读视频或片段 | "explain how Shazam works"、Sam Altman 片段 | 8,219 赞 / 6,651 收藏；1,055 赞 / 1,878 收藏 |
| 梗图或反应图 | Meta 高级程序员修 bug、"git push" | 6,918 赞；1,548 赞 |
| AI 或工具干了出人意料的事的截图 | Claude via Cursor | 3,748 赞 |
| 别人的规则或打法的图片、幻灯片 | YC 冷邮件规则、Nikita Bier | 3,611 收藏；2,881 收藏 |
| 一张引人反思的图（"this picture"） | 换个角度看的图 | 2,049 赞 |
| 用产品做的演示视频 | 法拉利发布视频 | 733 赞 |
| 图表 / 示意图 | "Average journey of a startup founder." | 725 赞 |

规则：
1. 媒体要能独立成立：截图本身就是证据，视频本身就是价值。
2. 帖子文字用 1–3 行把媒体框起来，不要重复图里已有的内容。
3. 想要收藏，用信息密集、能反复用的图（规则、框架、清单、带标注的截图）。
4. 想要曝光，用一眼就懂的图（梗图、反应图、一张抓人的照片）。
5. [通用] 截图裁到重点，手机上文字要看得清，画面只有一个焦点。

---

## 7. 线程和长帖

**数据显示的情况。**
- 样本中有 31 条帖子在开头写了 "thread" 或 🧵。中位数 70 赞，整体是 40 [数据]。最好的几条：
  - "I had to face 2 shutdowns…"（1,529 赞）
  - "Imagine being early on crypto… 5 predictions"（352 赞）
  - "Why now is the best time to bootstrap a million dollar startup"（274 赞）
- 线程的正文（第一条之后的部分）无法分析。
- 2023 年以来，他大多改发单条**长帖**（280–1,100 字符），不再发线程。他近期收藏最多的清单，1,079 字符的 "6,000+ tweets"，就是一条单独的长帖。

[通用] 需要写线程时怎么写：
1. 第一条承担全部任务：开头 + 承诺（"17 tools"、"12 growth tips"、"the full story"），以 👇 结尾。
2. 每条一个意思，每条被单独截图时也要能看懂。
3. 给每条或每项编号，让读者知道读到哪了。
4. 至少每 2–3 条放一个证据（图或数字）。
5. 最后一条用一句话总结，加一个温和的行动号召（关注 / 收藏 / 链接）。他反复发的 Newsletter 推广只有 0–7 赞，所以号召要短，并且放在给出价值之后。
6. 1,500 字符以内能写完的，优先发单条长帖。更简单，而且整条都会被读到。

---

## 8. 回复与引用转发

**数据显示的情况（有限）。**
- 引用转发：中位数 22 赞（n=196）。原创：43 赞 [数据]。
- 他 2021 年 6 月的回复样本（n=25）：中位数 1 赞，最高 3 [数据，样本小]。早期回复本身几乎没带来互动。它的价值在于建立关系、让原帖作者看到你，这份数据量不出来。
- 他在 2026 年的清单里说 "replies beat posts when you're small. your post gets 50 views, a good reply on a viral post can get 50k"。这是他的说法，这里没有验证。
- 他的 "pro tip: like posts from people < 1k followers / they'll see you in their notifs"（413 赞）是一个相关的低成本技巧。

规则 [通用，与数据一致]：
1. 回复刚发出不久（约 1 小时内）、比你大 2–20 倍的账号，你的回复有机会排到前面。超大爆款下的回复会被淹没。
2. 每条回复都要补一样东西：一个数字、一个反例、一个漏掉的步骤，或一个小故事。不要说"写得好"。
3. 回复里不放链接，不推销自己。
4. 引用转发必须加入新的判断。否则就直接回复，或者就这个话题自己写一条原创。他只夸不加内容的引用（"What a thread!"）只有 1 赞。
5. 某条回复效果好，第二天把它改成一条原创。

回复模板 [通用]：
- **补数字：**"Matches what I saw: [X out of Y] when I [did Z]."
- **边界情况：**"True for [A]. Breaks for [B], because [reason]."
- **漏掉的步骤：**"The step people skip: [step]. Without it, [consequence]."
- **小故事：**"Tried this last [month]. [Result with a number]. The surprise was [detail]."
- **说得更透：**"Shorter version: [one-line reframe]."
- **礼貌反驳：**"I'd push back on [point]: [evidence]. Curious if you've seen [case]."
- **实际问题（先给价值再问）：**"[Your add]. How do you handle [specific sub-problem]?"

---

## 9. 按目标分类的填空模板（26 个）

每个模板都参照了一条真实帖子（写在模板下面）。

### 目标：收藏
1. **专家的 N 条规则**
   `a [credentialed person] who [proof] just laid out [N] rules for [topic]` + 规则的图片
   参照：YC 合伙人 8 条规则（3,611 收藏）
2. **[知名事物] 是怎么运作的**
   `"explain how [thing] works"` / `[真实反应]` / `[权威] is right about this` / `[一句话预测]` + 视频
   参照：Shazam（6,651 收藏）
3. **这就是 [某人] 做到 [结果] 的方法**
   `this is how [person] [achieves result]` + 1–2 张图
   参照：Nikita Bier（2,881 收藏）
4. **我分析了 N 个**
   `I [做了大量调研：N 个对象]. [发现了什么], short list 👇` + 5–8 条，每条带数字 + `(bookmark this)`
   参照：6,000+ 条推文（2,332 收藏）；5,000+ 个账号（1,039 收藏）
5. **战绩 → 资源清单**
   `I've [战绩 1], [战绩 2], and [带金额或数字的战绩 3]` / `The secret: [一个论点]` / `The [N] [tools/steps] that [好处] 👇`
   参照：3,434 赞 / 3,161 收藏
6. **大师课 + 我的笔记**
   `[Who] just dropped a masterclass on [topic]. I've added my notes alongside.` + 带标注的图
   参照：610 收藏
7. **大号的过去与现在**
   `In [year], [person] didn't have [X]. Today [大数字]. I studied [it], here are [N] tips:`
   参照：Sahil Bloom（528 收藏）
8. **最佳资源合集**
   `built the best resource for [task] / including the [N]+ best [examples] / [质量证明] / start here: [link]`
   参照：610 收藏

### 目标：曝光和点赞
9. **金额反差梗**
   `* [Role] paid $[大数] for [job] *` / `[铺垫]` / `[笑点] 👇` + 图
   参照：6,918 赞
10. **"me when" 圈内梗**
    `me when I [圈内动作]` + 图
    参照：1,548 赞
11. **AI 或工具干了怪事**
    `LOL!! [tool] randomly [意外动作] 🤯` / `([为什么出乎意料])` + 截图
    参照：3,748 赞
12. **花小钱，结果离谱**
    `handed [tool] [小金额 / 资源]` / `[最少的操作]` / `[带数字的离谱结果]` / `[真实反应]` / `[更大的观点]`
    参照：1,612 赞
13. **引人反思的图**
    `I keep coming back to this [picture/chart]` / `[它对你的意义]` + 一张有冲击力的图
    参照：2,049 赞

### 目标：涨粉和信任
14. **失败次数 → 成功**
    `I had to face [N 次失败], [N 次挫折], and [N 年] to finally [带金额或数字的成功].` / `[为什么现在分享]` 👇
    参照：1,529 赞
15. **过去 vs 现在的时间线**
    `[年份]: [emoji] • [错误 ×4–5]` / `[年份]: [emoji] • [改变 ×4–5]` / `[一句话教训]`
    参照：413 赞 / 223 收藏
16. **坚持的回报清单**
    `I [做了某件小事] every day for [N years]. It brought me: - [数字] - [数字] - [数字]` / `[教训]`
    参照：476 赞
17. **和知名同行的私下谈话**
    `before [重大决定], I had a long talk with [知名人物]` / `they almost convinced me [X]` / `their reasoning: - … - …` / `[后来怎样]`
    参照：680 赞
18. **荒诞的自画像（生活）**
    `guys, I had no clue, but [同时做 N 件事] with [N 个生活细节] is so freaking hard`
    参照：772 赞

### 目标：回复
19. **开放舞台**
    `Are you [building/doing X]? / Congrats! / Here's your chance. / Share [你的链接 + 一句话介绍] 👇`
    参照：562 赞
20. **新闻 + 问大家**
    `it's done / [一句话说明平台变化] / so tell me: / [关于读者亲身经历的具体是非题]`
    参照：629 赞
21. **招人 / "谁能做这个"**
    `if anyone reading this can create this, DM me / I'll [有吸引力的回报].` + 例子
    参照：963 赞

### 目标：产品案例（产品永远不打头）
22. **蹭新闻演示**
    `[大新闻] / so I made [作品] for them / (using [product] obviously 😅)` + 作品
    参照：法拉利，733 赞
23. **里程碑 + 什么起了作用**
    `[product] reached $[MRR] [emoji] / what worked for us: ✅ … ✅ … ✅ …`
    参照：343 赞 / 195 收藏
24. **用户成功案例**
    `I am [情绪] right now / this [user] uses [product] and just reached [对方的数字] / [谦虚地归功]`
    参照：367 赞 / 326 收藏
25. **先讲读者的赚钱好处**
    `new way to [带金额的好处]: / 👉 [在 product 上做什么] / [用 2–3 行说清怎么运作]`
    参照：364 赞 / 466 收藏
26. **专家资源 → 免费工具**
    `[expert] charges $[X] for [advice] / [稀缺性] / so we turned [it] into a free [tool] / it tells you: - … - … / [在哪拿]`
    参照：257 赞 / 521 收藏

---

## 10. 内容日历、发帖时间和旧帖再利用

### 10.1 发帖量
- 抽样月份里，他在月末 4–10 天内发了约 25 条原创，近几年大约每天 3–6 条原创，另加回复。早期发得少一些。
- [通用] 对大多数人来说，每天 1–2 条原创加 3–10 条高质量回复是能坚持下去的量。

### 10.2 每周格式搭配 [通用，按数据加权]

| 星期 | 格式 | 目标 |
|---|---|---|
| 周一 | 整理解读 + 媒体 | 收藏 |
| 周二 | 个人数字或故事（成功或失败） | 信任 |
| 周三 | 带数字的长清单帖（400–1,000 字符） | 收藏 |
| 周四 | 梗图 / 圈内笑话 / 截图 | 曝光 |
| 周五 | 反常识观点或 "pro tip" | 回复 + 曝光 |
| 周六 | 生活帖（真实细节） | 拉近关系 |
| 周日 | 故事形式的产品案例，或重发爆款 | 转化 |

以产品为主的帖子最多约每 7 条一条。他的产品帖中位数最低。

### 10.3 发帖时间 [数据，他的账号；请按你的受众调整]

他在法国发帖。各时段点赞中位数，换算成 UTC+8：
- **最好：**17 点（60 赞）、18 点（67）、20 点（57.5）。也就是 UTC 9–12 点：欧洲中午、美国东部早上。
- **最差：**UTC+8 凌晨 1–6 点（1–15 赞）。

规则：在你的核心受众醒着、坐在电脑前的时候发。受众主要在美国，就发在美国早上到午饭前。测试 2–3 个时段，每个测 2 周，比较中位数。

### 10.4 重发爆款 [数据]

| 原帖 | 重发 | 结果 |
|---|---|---|
| "I had to face 2 shutdowns, 1 bankruptcy…" 2023-11-28，1,529 赞 | 2024-02-22 | 246 赞（16%） |
| "These guys just dropped a masterclass…" 2025-02-18，373 赞 | 2025-08-29 | 94 赞（25%） |
| "influencer marketing is going to get very weird" 2026-05-26，72 赞 | 2026-05-30 | 75 赞（约 100%） |
| Newsletter 推广 "Sharing the playbook…" | 8 天发了 6 次 | 每次 0–7 赞 |

规则：
- 只重发验证过的爆款，隔 2–6 个月，换一个开头或换一张图。
- 预期能拿到原帖的 15%–100%。越大的爆款，衰减越多。
- 广告不要高频重发。

---

## 11. 发帖后的复盘流程

[通用，按数据调整]

1. **发出 1 小时：**看曝光和回复。早期的每条回复都回，让讨论继续下去。
2. **发出 24 小时：**把曝光、点赞、收藏、回复、主页访问 / 涨粉记到表里。给每条帖子打标签：话题、开头类型、长度区间、有没有媒体、发帖时段。
3. **每周：**按标签算中位数，不要算平均数。做出你自己版本的 §2 和 §4 那几张表。
4. **改写规则：**一条帖子 24 小时后排在你自己后 25%，**而且**你仍觉得这个点子好，就改写开头（见 §12），3–14 天后再发一次。不要删原帖。
   - 他说有一次改写把一条帖子从 7 赞变成 380 赞。这是他的说法，这份数据里没有验证。
   - 大号可以很快重发。小号 30 分钟的数据不够判断，用 24 小时。
5. **放大爆款：**排在你前 10% 的帖子可以变成：
   - 扩写成长帖或线程，
   - 2–6 个月后的重发版本，
   - 置顶帖（如果内容不过时）。
6. **要盯的比例：**
   - 收藏 / 点赞高于约 0.5，说明这种格式值得收藏（他的整理类帖子在 0.8–2.7 之间）。多做这种。
   - 回复 / 点赞高于约 0.2，说明这是个能聊起来的话题。可以接着发一条。

---

## 12. 检查清单与改写

### 12.1 发帖前检查清单
- [ ] 第一行有具体的数字、金额、人名或具体事物。
- [ ] 第一行是陈述句（或者是一个能筛出特定人群、**并且**给他们回复理由的问题）。
- [ ] 只讲一件事。读者能用 5 个词说出它在讲什么。
- [ ] 有证据：数字、截图或亲身经历。不写自己证明不了的说法。
- [ ] 格式和目标匹配（§2.2）：要收藏就写长，要曝光就短帖加媒体。
- [ ] 意思之间有换行，列表只用一种符号。
- [ ] 能配媒体就配，而且媒体要提供信息。
- [ ] 正文不放链接，除非价值已经讲完（否则放在回复里）。
- [ ] 如果提到产品，它是案例或括号里的补充，不是标题。
- [ ] 0–3 个 emoji，每个都有作用。
- [ ] 发帖时间在受众的活跃时段内。
- [ ] 诚实：没有编造，没有把别人的经历说成自己的。

### 12.2 改写检查清单（适用于弱稿或发了没水花的帖）
1. 把最惊人的数字挪到前 8 个词里。
2. 把形容词（"amazing"、"must have"、"really good"）换成一个可测量的结果。
3. 把问句开头改成"我发现了什么"的陈述。
4. 第一句如果只是热身，删掉。
5. 加一句"为什么是你"（一项战绩，或你做过什么）。
6. 有 3 个以上要点就用列表。
7. 配上媒体，或者把链接换成截图。
8. 用一句结论收尾，不要用 "thoughts?"。

### 12.3 改写前后示例（"改写前"是他真实的低表现帖，"改写后"套用的是他自己的高表现写法）

1. **改写前：**"built in [link] / try it, it's really good" —— 8 赞
   **改写后**（套路：蹭新闻演示，733 赞）："[Brand] just launched [X] / so I made their launch video in one prompt / (built with [tool] 😅)" + 视频。
2. **改写前：**"if you're serious about X, the SuperX extension is an absolute must have" —— 2 赞
   **改写后**（套路："我分析了 N 个"，2,332 收藏）："I tested [N] X tools for [N] days. Only [N] changed my numbers. Short list 👇 1. [tool]: [指标前 → 后]…"
3. **改写前：**"How I got 15% new followers with a single tweet" —— 3 赞（2021）
   **改写后**（套路：硬数字 + 方法，1,202 赞）："1 post brought me [N] new followers in [N] hours. Here's exactly what it had: 1. … 2. … 3. …"
4. **改写前：**"Does it help you prioritizing tasks or does it get you anxious?" —— 0 赞
   **改写后**（套路：奇怪的领悟，318 赞）："i had a weird realization: my to-do list made me slower. I cut it from [N] items to [N]. Shipped [result] in [time]."
5. **改写前：**"Never give up!" —— 0 赞
   **改写后**（套路：失败次数 → 成功，1,529 赞）："[N] failed launches. [N] months with $0. Launch #[N] made $[X] in week one. What changed: [one thing]."
6. **改写前：**"Sharing the playbook that turned years of failure into an $8m acquisition…"（推广发了 6 次）—— 0–7 赞
   **改写后**（套路：专家资源 → 免费工具，521 收藏）："[Expert] charges $[X]/hour for this playbook / so I wrote down the [N] steps for free / 1. … 2. … / full version in my newsletter (link in reply)."

---

## 13. 小号（粉丝不到 1,000）怎么用

1. **接受慢启动。** 他 2020 年点赞中位数是 1，庆祝 1,000 粉的帖子只有 3 个赞。用 8–12 周的中位数评判策略，不要看单条。
2. **借来的权威胜过自己的权威。** 没有战绩时，整理解读（"this is how [名人] does X"、"[专家] 的 N 条规则"）是最容易上手的爆款格式。加一句自己的看法。
3. **没有金额数字，就用过程数字。** 花了多少小时、测了多少个、错误率、一次实验的前后对比。"第一行放数字"不一定要是钱：第一行有任何数字的帖子，点赞中位数是 45，没有的是 37 [数据]。
4. **回复就是分发渠道。** 每天在刚发出的中等体量帖子下写 1–2 条高质量回复（§8）。也和粉丝不到 1,000 的人互动，他们会注意到你。
5. **小号写长帖照样有用。** 就算点赞少，收藏也是很强的信号。
6. **别过度重发，也别删帖。** 没水花的帖等 24 小时后再改写，不要 30 分钟就动。
7. **战绩会累积。** 每一个真实的里程碑（第一个用户、第一笔收入、第一批 100 个粉丝）都是以后的开头素材。记下来。
8. **产品占比要低。** 即便对他来说产品帖也是最弱的话题，从一个陌生账号发出来更像广告。

## 14. 小众或技术话题怎么写

1. **先讲利害。** 先说后果（"10 秒烧掉 40 美元"、"722 篇里有 3 篇出了问题"），再讲原理。
2. **解读是你的优势。** "[熟悉的东西] 是怎么运作的" 是他排第一的帖子。技术人做这种内容最在行。挑你的受众已经认识的东西。
3. **圈内幽默有效。** 程序员梗（"Regex… Stackoverflow"，578 赞；"git push"，1,548 赞）说明小众笑话能在圈内传得很远。
4. **用截图当证据。** 带标注的输出、报错信息、基准测试结果，就是技术版的"有价值的媒体"。
5. **每条帖子最多一个术语，顺带解释。** [通用]
6. **数字带单位和分母**（写"40 个里有 11 个"，不写"27%"）。他的弱开头 "15% new followers" 和强开头 "6,000+ tweets" 指向同一个方向。[方向性]
7. **反常识观点需要证据。** "Most of the growth advice is horse shit" 拿到 334 收藏，是因为后面跟了一串理由。

---

## 15. 被要求写帖子时的快速流程

1. 问清楚或推断出：目标（收藏 / 曝光 / 涨粉 / 回复 / 产品）、受众、手上有什么证据。
2. 选一个选题类别（§3）和一种格式（§2.2）。
3. 挑 2–3 种开头写法（§4），写出 3 个第一行备选。
4. 套一个模板（§9），能加数字的每一行都加上数字。
5. 过一遍发帖前检查清单（§12.1）。
6. 建议配什么媒体、什么时间发（§6、§10.3）。
7. 交付草稿和 2 个备选开头。用户没有明确要求，绝不替用户发帖。
8. 绝不编造数字、经历或引语。缺证据的地方标上占位符 [NEED: number]。
