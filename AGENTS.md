# AGENTS.md

## Current state
- This is not a code project yet. There is no git repo, package manifest, build, test, lint, CI, or OpenCode config. Do not invent commands; verify before assuming any exists.
- The only file is `чат о рынок Сочи сервисных компаний_сайт.md` (UTF-8, ~1050 lines), a saved chat transcript in Russian, not a spec. Quote the filename in shell commands.
- The transcript has two parts: market research on Sochi service companies and SMB automation consulting (sections 1–11), then a planned personal portfolio site ("Контекст: личный сайт-визитка", near the end).

## Treat the transcript as source material
- Market figures, prices, competitor claims, and cited links are unverified; the transcript says so itself. Do not present them as facts on a site or in deliverables without checking.
- Some turns quote other repos (`tender-platform`, `Content_Factory`) and their tooling (ruff, alembic, pytest, docker compose, nginx). Those are not in this directory; do not apply them here.
- The file contains personal job-search and contact plans. Do not copy them into a public repo or site without the user's explicit approval.

## Planned project: personal portfolio site
- Goal: one "business card" site as the hub for direct clients, subcontracting for integrators/agencies, employers/HR, and freelance-platform visitors. Each audience gets its own entry point; do not mix their messages on one headline.
- Planned hosting: GitHub repo plus GitHub Pages or Cloudflare Pages, with a custom domain. The stack is not chosen (the transcript suggests a static generator or plain HTML/CSS). Confirm with the user before scaffolding a framework.
- Site copy is planned in Russian for a Russian-speaking audience.
- Avoid collecting personal data. A form on static hosting needs a third-party service and falls under ФЗ-152. Start with a mailto or Telegram link.
- Per the plan, do not add calculators or extra pages before real case studies exist. Do not invent case metrics. Ask the user for the facts: what was done, the measured results, and the tools used.
