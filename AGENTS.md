# AGENTS.md

Put this file in the repository root. Codex reads AGENTS.md. For Claude Code, add a CLAUDE.md that contains one line: @AGENTS.md

## Project
What this project is, in two sentences.

## Build and test
- Build: `...`
- Unit tests: `...`
- Lint/format: `...`
- iOS only (macOS nodes): `xcodebuild -scheme ... -destination 'platform=iOS Simulator,name=iPhone 16' test`

## Rules
- Keep changes small and inside the scope of the issue.
- Do not add dependencies without a reason in the summary.
- Do not touch signing, provisioning profiles, secrets, or CI files.
