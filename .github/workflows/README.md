# Workflows

| Workflow | Runs on | What it does |
| --- | --- | --- |
| [`markdownlint.yml`](markdownlint.yml) | Push to `main`, every pull request | Lints every markdown file against [`.markdownlint.json`](../../.markdownlint.json) |
| [`gitleaks-scan.yml`](gitleaks-scan.yml) | Every push, every pull request | Scans the working tree for hard-coded secrets with a pinned Gitleaks binary and fails if it finds one |

Both also run by hand, via `workflow_dispatch` from the Actions tab. Third-party actions are pinned to a full commit SHA, so a moved tag cannot change what runs.
