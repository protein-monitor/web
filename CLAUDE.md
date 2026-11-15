# CLAUDE.md

## What this repo is for
`web` is the frontend of the protein-tracker project. It currently
contains only a README , a pull request template and the GitHub configuration. No application code yet.

## Conventions
- Every branch, commit and PR title starts with the Jira key (e.g. `PRT-27`).
- Flow: branch -> pull request -> 1 approval from the team lead -> merge.
- `main` is protected: never push directly to it.
- Fill in the pull request template for every PR.

## Hard rules
- Never commit secrets (API keys, passwords, tokens, .env files).
- Every code change comes with tests.
