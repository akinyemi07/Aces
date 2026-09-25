# Contributing to ACES GLOBAL LOGISTICS

## Development Workflow

ACES follows a trunk-based development workflow.

The `main` branch is the shared integration branch. Changes should not be committed directly to `main`.

Development work should use short-lived branches:

- `feat/...` — new features
- `fix/...` — bug fixes
- `chore/...` — maintenance, documentation, tooling, and repository work

## Pull Requests

All changes should reach `main` through a pull request.

A pull request should:

1. Explain what changed.
2. Explain why the change was needed.
3. Keep the change focused.
4. Be reviewed before merging.
5. Use a clear Conventional Commit-style title where appropriate.

Pull requests should be squash-merged into `main`.

## Commits

Commit messages should follow the Conventional Commits format.

Examples:

```text
feat: add user registration
fix: handle invalid input
docs: update project roadmap
chore: configure repository workflow
