# Changelog

All notable changes to this repository are recorded here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

---

## [Unreleased]

### Added

- `ACCESSIBILITY.md`, a default accessibility statement for every repository owned by this account, pointing at the owner's shared statement on GitHub and on the website
- `.github/FUNDING.yml`, so a repository here carries the owner's sponsor links
- `.github/workflows/README.md`, describing the two workflows
- `.github/dependabot.yml`, for weekly GitHub Actions updates
- This changelog

### Changed

- `SECURITY.md` and `CODE_OF_CONDUCT.md` carry a callout for the private reporting route and link the owner's full policies
- `CONTRIBUTING.md` and `SUPPORT.md` treat an accessibility barrier as a bug and point at `ACCESSIBILITY.md`. `CONTRIBUTING.md` refers to the owner in the third person
- The README lists every file here and what it is for
- The issue form contact links cover the code of conduct, the contributing guide and the accessibility statement. Every issue form assigns the owner
- The pull request template links the community files by full URL, since a pull request body cannot resolve relative links
- The Gitleaks scan can also be run by hand, its header describes this repository and its checkout pin matches the lint workflow

## [2026-09-29]

### Added

- `README.md`, `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`, `SUPPORT.md` and the MIT licence
- Issue forms for bugs, feature requests, improvements, documentation and questions, with blank issues disabled and contact links
- A pull request template
- `.markdownlint.json` with a markdown lint workflow and a Gitleaks scan
