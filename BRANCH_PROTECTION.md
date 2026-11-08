# Branch Protection Policy

This is the branch protection policy I aim to follow in my repositories. GitHub does not apply it automatically: each repository needs these rules configured under **Settings → Rules → Rulesets** (or **Settings → Branches**), and may extend them as needed.

## Protected Branches

- `main`
- `production` (where applicable)

## Rules

### Direct Pushes

❌ Direct pushes are avoided on protected branches.

Changes should be submitted through Pull Requests where the repository has other contributors. Trusted automation, such as a stats update bot, may commit directly.

### Pull Requests

- CI checks must pass (where the repository has CI)
- No force pushes to protected branches

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

- Enable secret scanning and push protection under **Settings → Code security**
- Enable Dependabot alerts, and add a `.github/dependabot.yml` listing the repository's package ecosystems (composer, npm, github-actions, …). See this repository's [dependabot.yml](.github/dependabot.yml) for an example.
