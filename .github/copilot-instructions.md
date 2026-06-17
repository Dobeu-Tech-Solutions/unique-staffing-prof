# Copilot Instructions

> Automatically given to GitHub Copilot for every task in this repository.
> Keep it short, factual, and current. Replace the bracketed placeholders.
> (This repo also has a CLAUDE.md with deeper project conventions.)

## What this project is

[One or two sentences: what the app does and who uses it.]

- **Primary language:** TypeScript
- **Package manager:** [pnpm / npm — confirm]

## How to build, test, and lint

```bash
[install]    # e.g. pnpm install
[build]      # e.g. pnpm build
[test]       # e.g. pnpm test
[lint]       # e.g. pnpm lint
```

A change is not done until build, tests, and lint pass.

## Coding standards

- Follow the existing style in the file you are editing.
- See CLAUDE.md for project-specific conventions and architecture.
- Keep public APIs documented; update docs when behavior changes.

## Things to avoid

- Do not commit secrets, tokens, or `.env` files.
- Do not edit generated files or lockfiles unless that's the task.
- Do not add dependencies without justification in the PR description.

## Pull request expectations

- Small, focused PRs. Describe what changed, why, and how it was tested.
