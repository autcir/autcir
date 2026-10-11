# Changelog

Notable changes to this GitHub profile repository. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and the project
uses [Semantic Versioning](https://semver.org/) for its tags.

## [Unreleased]

### Added

- `scripts/update_stars.py`: regenerates `STARS.md` from the public GitHub
  Lists through the GraphQL API; `--check` reports a stale file
- `assets/typing.svg`: the profile banner as a static file in the repository
- Markdown lint, link check and gitleaks workflows, plus a markdownlint config
- README section explaining how the snake animation is produced

### Changed

- `STARS.md` is generated from the Lists, carries a snapshot date and no
  longer lists star counts (they went stale immediately)
- All GitHub Actions are pinned to full commit SHAs; workflows use minimal
  `permissions`, `concurrency` and timeouts; `snake.yml` no longer runs on
  push to `main` (cron and manual run only)
- The release workflow writes its notes outside the checkout and publishes
  with the `gh` CLI instead of a third-party action
- Dependabot: grouped updates with a 7-day cooldown
- `SECURITY.md` lists a working reporting path and the supported versions
- Release link now points to the `autcir/autcir` repository

### Removed

- `generate-snake.sh`: the snake is produced by the `snake.yml` workflow
- The `readme-typing-svg.herokuapp.com` / `git.io` dependency in the README
- `organize_github_lists.py` (the "auto-sorting script" listed under 1.0.0) had
  already been deleted in 5cfbbab; `scripts/update_stars.py` replaces it

## [1.0.0] - 2026-07-28

### Added

- Profile README with project showcase and activity stats
- `STARS.md`: categorised showcase of starred repositories, with an
  auto-sorting script
- Contribution snake animation, generated locally via Docker
- `SECURITY.md`, `.editorconfig`, Dependabot, and a release workflow

[Unreleased]: https://github.com/autcir/autcir/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/autcir/autcir/releases/tag/v1.0.0
