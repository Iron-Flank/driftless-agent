# AGENTS.md

Instructions for AI coding agents working in the **driftless-agent** repository.

## Project Overview

driftless-agent is a self-hostable agent runtime extracted from the driftless platform. It is released under the [MIT License](./LICENSE) and is built for long-horizon, multi-session agent work.

Core capabilities:

- **Persistent memory** — agents retain and recall context across sessions.
- **SOUL injection** — inject persona and behavior directives into agent prompts.
- **Conversation management** — coordinate multi-turn, multi-session conversations.

## Repository Structure

The runtime is being extracted from the driftless platform monorepo. The repository is not yet scaffolded beyond the initial files (`README.md`, `LICENSE`, `.gitignore`); no runtime source has been extracted yet.

Key directories and their purpose will be documented here once the codebase is extracted and laid out. Until then, treat this repo as pre-scaffold: only top-level documentation and license files are present.

## Contributing

1. **Fork** the repository, then create a feature branch from `main` (e.g. `feat/<short-slug>` or `fix/<short-slug>`).
2. Make your change, keeping the pull request **focused and small** — one concern per PR.
3. **Follow existing code style.** Match the conventions already present in the codebase; do not introduce a second style alongside an existing one.
4. Open a **pull request** to `main` describing what changed and why, then **enable auto-merge** so the PR merges to `main` automatically once checks pass. See [Git Workflow](#git-workflow) for the full steps — there is no manual reviewer-merge step.

## Git Workflow

Contributions land on `main` through pull requests with auto-merge enabled. There is no manual reviewer-merge step.

1. **Push to a feature branch.** Create a branch from `main` (e.g. `feat/<short-slug>` or `fix/<short-slug>`), commit your change, and push it to the remote.
2. **Open a PR against `main`.** Describe what changed and why; keep the PR focused on one concern.
3. **Enable auto-merge.** Turn on auto-merge on the PR so it merges to `main` automatically once any configured checks pass. No manual merge step is required.

### CI Checks

No CI checks are configured yet — there are currently no automated build, test, or lint gates. CI may be added in the future; when it is, auto-merge will gate on those checks automatically. Until then, be ready to share the exact commands you ran to verify your change locally.

## License

This project is licensed under the [MIT License](./LICENSE). By contributing, you agree that your contributions are licensed under the MIT license.