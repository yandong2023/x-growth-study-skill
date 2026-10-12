# X Growth Study Skill

An agent skill for studying any benchmark X (Twitter) account's posting history and turning it into a data-backed posting playbook.

It tells an AI agent how to:

- pull a sample of an account's posts across its whole history, within API read limits
- analyze growth over time, post length, media, hooks (numbers, $ amounts, questions vs statements), topics, and posting hours, using medians
- state the sampling caveats honestly
- produce a report, a playbook, and a draft post built only on real numbers

The skill does not publish anything. It hands drafts back for a person to post, and it must not invent statistics.

## Example findings

One sample of 1,047 original posts from a founder account with 210K followers, covering 2020–2026:

- Median likes per post: 1 in 2020, 18 in 2021, 39 in 2022, 89 in 2026.
- A $ amount in the first line: median 133.5 likes vs 37 for other posts.
- Posts over 280 characters: median 38–68 bookmarks vs 1–2 for shorter posts.
- Posts with media: median 60 likes vs 33 text-only.

These figures describe that one sample only.

## Use

Copy `SKILL.md` into your agent's skills folder (Claude Code, Codex, or any agent that reads `SKILL.md` files). It assumes the agent has X read tools: user lookup, user posts, and post search.

## License

[MIT](LICENSE) — Copyright 2026 yandong2023.
