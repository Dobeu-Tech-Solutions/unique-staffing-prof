# GitHub Cloud Agents - Setup & Best Practices

This repo already has ai-code-review and other CI workflows, so this PR is
additive: it adds Copilot coding-agent instructions and environment setup only.

## Files added here
- `.github/copilot-instructions.md` - steers GitHub Copilot (coding agent, review, chat)
- `.github/workflows/copilot-setup-steps.yml` - pre-installs deps for Copilot's agent env

## To also add the interactive @claude agent
Copy `claude.yml` from the dobeu-devop-enforcer pilot (or ask), add the
`ANTHROPIC_API_KEY` secret, and install the Claude GitHub App. We skipped it
here to avoid overlapping with your existing review automation.

## Activate Copilot coding agent (owner-only)
Requires a qualifying Copilot plan; enable in Settings > Copilot > Coding agent.
Then fill the bracketed placeholders in copilot-instructions.md / copilot-setup-steps.yml.
