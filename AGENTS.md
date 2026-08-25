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
4. Open a **pull request** to `main` describing what changed and why.

### No CI/CD

No CI/CD pipeline is configured yet — there are no automated build, test, or lint gates. **Reviewers validate builds and tests locally** before merging a pull request. When you open a PR, be ready to share the exact commands you ran to verify your change.

## License

This project is licensed under the [MIT License](./LICENSE). By contributing, you agree that your contributions are licensed under the MIT license.