# Contributing Guide

Thanks for your interest in contributing. This guide covers this repository. My other repositories follow the same process unless they include their own `CONTRIBUTING.md`.

## Getting Started

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Commit your changes
5. Push your branch
6. Open a Pull Request

## Branch Naming

```
feature/feature-name
bugfix/issue-name
hotfix/issue-name
```

## Commit Convention

I follow [Conventional Commits](https://www.conventionalcommits.org/):

```
feat:     new feature
fix:      bug fix
docs:     documentation
refactor: code cleanup
test:     tests
chore:    maintenance
```

## Pull Requests

- Keep pull requests focused and reasonably small
- Reference any related issue (e.g. `Closes #123`)
- Make sure CI checks pass before requesting review (where the repository has CI)

## Code Standards

- Follow PSR-12 for PHP code (adjust to the relevant language/style guide for non-PHP repos)
- Write clean, readable code
- Add or update documentation for any user-facing change
- Add or update tests where the project has them
- Never commit secrets, credentials or `.env` files

## Code of Conduct

All contributors are expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
