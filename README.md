# zaccesssbot

Automation on behalf of [@zaccesss](https://github.com/zaccesss). This account does mechanical,
non-authorship work only: repo housekeeping, scheduled refreshes and similar tasks. It never does
creative or judgement based work. It never claims reviewer or maintainer status on anything.

- Main account: [github.com/zaccesss](https://github.com/zaccesss)
- Site: [isaacadjei.me](https://isaacadjei.me)

This repository supplies the default community health files for any repository owned directly
by this account. GitHub falls back to the files here for a repository that does not carry its
own copy.

## What is here

- [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) - how interactions on this account's repositories are expected to go.
- [`CONTRIBUTING.md`](CONTRIBUTING.md) - what is open to contribution here and where a fork's issues belong.
- [`SECURITY.md`](SECURITY.md) - how to report a security issue privately.
- [`SUPPORT.md`](SUPPORT.md) - where to go for help.
- [`ACCESSIBILITY.md`](ACCESSIBILITY.md) - how the documentation is written to be accessible and how to report a barrier.
- [`.github/FUNDING.yml`](.github/FUNDING.yml) - the owner's sponsor links.
- [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE) and [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md) - the default issue forms and pull request template.
- [`.github/workflows/`](.github/workflows) - the lint and secret scan that keep this repository itself tidy, described in [its README](.github/workflows/README.md).
- [`.github/dependabot.yml`](.github/dependabot.yml) - weekly updates for the actions those two workflows pin. It covers this repository only, since GitHub does not inherit it.
- [`.markdownlint.json`](.markdownlint.json) - the rules the markdown lint enforces.
- [`LICENSE`](LICENSE) - MIT.
- [`CHANGELOG.md`](CHANGELOG.md) - what changed here and when.

A repository with its own version of any of these overrides the default here.

## Notes

- The account's profile page is driven by [`zaccesssbot/zaccesssbot`](https://github.com/zaccesssbot/zaccesssbot), not this repository.
- Files GitHub does not inherit, such as `CODEOWNERS` and `dependabot.yml`, live in each repository that needs them.
- Every fork owned by this account is reset to its upstream every six hours, so it stays an exact copy. Issues and pull requests belong on the upstream project.
