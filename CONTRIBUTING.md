# Contributing to shepard-system

Thanks for your interest in contributing. This guide applies to **all repositories** in the organisation.

## Getting Started

1. **Fork** the repository you want to contribute to
2. **Clone** your fork locally
3. Create a **feature branch** from `main`: `git checkout -b feature/your-change`
4. Make your changes
5. **Commit** with a clear message (we prefer [Conventional Commits](https://www.conventionalcommits.org/))
6. **Push** to your fork and open a **Pull Request** against `main`

## Pull Request Guidelines

- Keep PRs focused — one logical change per PR
- Fill in the PR template
- Ensure CI checks pass before requesting review
- Link related issues using `Closes #123` or `Fixes #123`

## Commit Messages

We follow Conventional Commits:

```
feat: add cost breakdown to dashboard
fix: correct token count for streaming responses
docs: update installation instructions
chore: bump loki to 3.x
```

## Reporting Bugs

Use the **Bug Report** issue template. Include:

- Steps to reproduce
- Expected vs actual behaviour
- Environment details (OS, Docker version, etc.)

## Suggesting Features

Use the **Feature Request** issue template. Describe:

- The problem you're trying to solve
- Your proposed solution
- Any alternatives you've considered

## Code Style

- Follow existing patterns in the repository
- Keep it simple — don't over-engineer
- Add comments only where the logic isn't self-evident

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
