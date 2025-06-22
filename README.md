# ALXprodev-advanced_git

This repository implements the **Git-Flow branching model** for managing features, releases, and hotfixes in a structured and scalable way.

## Branching Strategy

- **main**: Production-ready code.
- **develop**: Integration branch for ongoing development.
- **feature/**: Feature branches for new development.
- **release/**: Branches for preparing releases.
- **hotfix/**: Branches for urgent fixes to production.

## Git-Flow Workflow

- Start new features from `develop`.
- Use pull requests to merge features back into `develop`.
- Create release branches from `develop` for final testing.
- Hotfixes branch off `main` for emergency fixes and merge back into `main` and `develop`.

## Getting Started

This repo is set up with Git-Flow initialized. Use git-flow commands for managing branches:

```bash
git flow feature start <feature-name>
git flow feature finish <feature-name>
git flow release start <version>
git flow release finish <version>
git flow hotfix start <version>
git flow hotfix finish <version>
