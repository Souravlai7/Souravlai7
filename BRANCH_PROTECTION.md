# Branch Protection Policy

This is the default branch protection policy for my repositories. Individual repositories should configure these rules under **Settings → Branches** and may extend them as needed.

## Protected Branches

- `main`
- `production` (where applicable)

## Rules

### Direct Pushes

❌ Direct pushes are avoided on protected branches.

Changes should be submitted through Pull Requests where the repository has other contributors.

### Pull Requests

- CI checks must pass
- No force pushes

### Commit Requirements

- Use meaningful commit messages
- Follow [Conventional Commits](https://www.conventionalcommits.org/)

Examples:

```
feat: add rate limiting middleware
fix: resolve pagination bug
docs: update setup instructions
```

### Security

- Secret scanning enabled
- Dependency scanning enabled ([dependabot.yml](.github/dependabot.yml))
