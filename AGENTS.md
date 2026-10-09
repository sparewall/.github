# AGENTS.md

Guidance for AI coding agents working in this repository.

- This repository holds organization-wide GitHub files only: the profile
  README, community health files and reusable workflows. There is no code
  to build.
- `profile/README.md` is public-facing; keep it short and accurate about the
  project's maturity.
- Reusable workflows under `.github/workflows/` must use `workflow_call`,
  pin third-party actions to a full commit SHA, and request the minimum
  `permissions`.
- The main project and its design live in
  [sparewall/sparewall](https://github.com/sparewall/sparewall).
