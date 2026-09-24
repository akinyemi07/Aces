# ADR 0001: Use a Monorepo

- **Status:** Accepted
- **Date:** 2026-09-18

## Context

ACES GLOBAL LOGISTICS will contain multiple components as development progresses.

Keeping related components in one repository provides a single location for project documentation, shared engineering standards, and the project's evolving components.

## Decision

ACES GLOBAL LOGISTICS will use a monorepo structure.

The repository will contain the project's related components and shared documentation under one Git repository.

## Consequences

### Positive

- One repository provides a single source of truth for the project.
- Project-wide documentation and standards can live alongside the code.
- Contributors have one repository to clone and understand.
- Changes affecting multiple components can be managed together.

### Trade-offs

- The repository will grow as more components are added.
- Contributors need to understand the repository structure.
- CI and tooling may eventually need to account for multiple components.

## Alternatives Considered

Separate repositories for each component were considered but were not selected for the initial project structure because the project benefits from a unified repository and shared engineering workflow.
