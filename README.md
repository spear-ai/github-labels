# github-labels

Spear AI GitHub labels. For use with with the [GitHub Label Sync](https://github.com/Financial-Times/github-label-sync#label-config-file) tool.

![checks](https://github.com/spear-ai/github-labels/actions/workflows/actions.yml/badge.svg)

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