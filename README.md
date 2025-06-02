# merendamattia/github-action

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Latest Release](https://img.shields.io/github/v/release/merendamattia/github-action?label=release)](https://github.com/merendamattia/github-action/releases)

[![Actions Status](https://github.com/merendamattia/github-action/actions/workflows/check-docker-image.yaml/badge.svg)](https://github.com/merendamattia/github-action/actions)
[![Actions Status](https://github.com/merendamattia/github-action/actions/workflows/check-latex-document.yaml/badge.svg)](https://github.com/merendamattia/github-action/actions)
[![Actions Status](https://github.com/merendamattia/github-action/actions/workflows/conventional-commits-check.yaml/badge.svg)](https://github.com/merendamattia/github-action/actions)
[![Actions Status](https://github.com/merendamattia/github-action/actions/workflows/semantic-release.yaml/badge.svg)](https://github.com/merendamattia/github-action/actions)


A customizable GitHub Actions setup to streamline and automate development workflows. Includes a Makefile for easy usage and integration.

Run `make` or `make help` to display this list of targets and their descriptions.

Full environment setup:
```bash
make setup
```

## Action supported
1. Git Conventional Commits check using [pre-commit](https://pre-commit.com/).
2. [Git Semantic Release](https://dev.to/sahanonp/how-to-setup-semantic-release-with-github-actions-31f3) using [action-for-semantic-release](https://github.com/marketplace/actions/action-for-semantic-release).
3. Auto Assign Pull Request by [kentaro-m/auto-assign-action](https://github.com/kentaro-m/auto-assign-action/tree/v2.0.0/).
4. Check Docker Image building.
5. Check LaTeX document building by [xu-cheng/latex-action](https://github.com/xu-cheng/latex-action/tree/v3/).

## Contributors

<a href="https://github.com/merendamattia/github-action/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=merendamattia/github-action" />
</a>
