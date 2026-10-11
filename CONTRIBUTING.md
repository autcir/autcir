# Contributing

This repository is my **GitHub profile** — its README is the landing page people see
when they open [github.com/autcir](https://github.com/autcir).

## What belongs here

- Fixes to the profile content: wrong links, outdated projects, broken badges
- Accessibility and rendering issues in `README.md`
- Improvements to the validation workflows (`.github/workflows/validate.yml`,
  `links.yml`, `snake.yml`)

## How to contribute

1. Fork the repo and create a branch from `main`
2. Make your change in `README.md`
3. Open a PR against `main`

CI (on the self-hosted soliso runner) runs markdownlint on all Markdown and a link
check on URLs — a red check blocks the merge, same as any other repo I maintain.

## What doesn't belong here

- Issues about my other projects → open them in those repositories instead
- Feature requests for the profile itself → open an issue first so we can discuss it

## Local checks before pushing

```bash
# markdown lint (same config as CI)
npx markdownlint-cli2 "**/*.md"

# link check (same config as CI: .lychee.toml)
lychee --config .lychee.toml README.md
```

Thank you for helping keep the profile accurate. 🙏
