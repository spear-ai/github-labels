# github-labels

Spear AI GitHub labels. For use with with the [GitHub Label Sync](https://github.com/Financial-Times/github-label-sync#label-config-file) tool.

[![checks](https://img.shields.io/github/workflow/status/spear-ai/github-labels/checks?labelColor=3A3a40&color=04C835&label=checks&logo=github)](https://github.com/spear-ai/github-labels/actions/workflows/checks.yml)
[![Conventional Commits](https://img.shields.io/badge/Conventional_Commits-1.0.0-ff206E.svg?labelColor=3A3a40)](https://conventionalcommits.org)

## Installation

```sh
yarn install
export GITHUB_ACCESS_TOKEN=<personal_access_token> # Optional
```

## Usage

```sh
yarn run sync:dry-run <repository>
yarn run sync <repository>
```
