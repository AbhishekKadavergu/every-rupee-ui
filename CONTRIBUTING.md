# Contributing to Every Rupee UI

Thanks for your interest in contributing to Every Rupee UI! We welcome contributions of all kinds — bug reports, feature requests, documentation improvements, and code. This document explains how to get started and what we expect from contributors.

## How to report issues

- Search existing issues to avoid duplicates.
- For bugs, include steps to reproduce, expected vs actual behavior, and environment details (OS, Node.js version).
- For feature requests, describe the problem, the proposed solution, and any UI/UX considerations.

## Getting started (development)

1. Fork the repository and clone your fork:

```powershell
git clone https://github.com/<your-username>/every-rupee-ui.git
cd every-rupee-ui
```

2. Install dependencies:

```powershell
npm install
```

3. Run the dev server:

```powershell
npm run dev
```

## Branching and pull requests

- Create a descriptive branch from `main`: `feature/your-feature-name` or `fix/short-description`.
- Keep changes focused and small where possible — one logical change per PR.
- Rebase or merge `main` before opening a PR to minimize merge conflicts.

## Code style

- Use TypeScript idioms consistent with the existing code.
- Keep formatting consistent; the repo uses basic CSS and React with TypeScript. If ESLint or Prettier are configured later, run them before committing.
- Write clear, descriptive commit messages (imperative mood):

  - `feat: add transaction form`
  - `fix: correct budget calculation`

## Testing

- Add tests for new functionality where practical. Include steps to run tests in your PR description.

## Pull request checklist

- [ ] The PR has a clear title and description.
- [ ] Related issue is referenced (if applicable).
- [ ] Code builds locally and the dev server runs without errors.
- [ ] Linting and/or tests have been run (if present).

## Communication

- If your change is large or will take time, open an issue first to discuss design/approach.
- Be respectful and constructive in comments. We aim to keep the project welcoming for all contributors.

## License and copyright

By contributing, you agree that your contributions will be licensed under the project's license (see `LICENSE`).

Thank you for helping improve Every Rupee UI!
