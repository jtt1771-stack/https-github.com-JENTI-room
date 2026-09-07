---
name: github-profile-design
description: Create or refine GitHub profile and repository READMEs using restrained layout, GitHub README Stats cards, and meaningful Markdown badges. Use for GitHub-facing identity and project presentation; do not use for application UI or general website design.
---

# GitHub Profile Design

Make the README useful first and visually polished second. Preserve accurate project information and the repository's established voice.

## Structure

- Lead with the project or person name and one specific sentence explaining the value.
- For repository READMEs, prioritize setup, usage, examples, status, and contribution information before decoration.
- For profile READMEs, surface current focus, selected work, relevant tools, and a clear contact path without turning the page into a wall of logos.
- Use standard Markdown and simple HTML only when GitHub rendering requires it. Keep the layout readable on narrow screens.

## GitHub README Stats

- Use `anuraghazra/github-readme-stats` cards only when they add information the audience benefits from.
- Prefer one or two coordinated cards over a dashboard of metrics. Match card colors to the surrounding README while preserving contrast.
- Never place access tokens, API keys, or private identifiers in image query strings, Markdown, workflow files, or committed configuration.
- Explain that third-party hosted cards may receive ordinary request metadata from visitors. Offer self-hosting when privacy, reliability, or private statistics materially matter.

## Markdown Badges

- Use badges for actionable status or durable facts: build, release, license, coverage, package version, or supported platform.
- Link badges to the relevant workflow, release, license, package, or documentation page.
- Keep label style, casing, color, and ordering consistent. Avoid vanity counters and long rows of technology badges that repeat the prose.
- Add concise alt text and percent-encode label values when constructing badge URLs.

Preview the rendered Markdown when possible and verify every link, image URL, and factual claim before delivery.
