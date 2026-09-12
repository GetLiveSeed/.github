# Contributing to LiveSeed

First off, thank you for considering contributing to LiveSeed! Open-source communities thrive because of people like you.

Please take a moment to review these guidelines before submitting an issue or pull request.

---

## Code of Conduct

This project and everyone participating in it is governed by the [LiveSeed Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

---

## How Can I Contribute?

### 1. Reporting Bugs
Before creating a bug report, please check existing issues to ensure it hasn't already been reported. When creating a bug report, include:
- A clear and descriptive title.
- Steps to reproduce the behavior.
- Expected vs. actual behavior.
- Screenshots or error logs if applicable.
- Environment details (Node.js version, OS, browser).

### 2. Suggesting Enhancements
Feature requests and architectural proposals are welcome!
- Check existing issues/discussions to avoid duplicates.
- Provide a clear problem statement and use-case explanation.
- Detail the proposed solution or API design.

### 3. Submitting Code Contributions

#### Branching Strategy
- Fork the repository and create your branch from `main`.
- Use descriptive branch prefixes:
  - `feat/feature-name`
  - `fix/bug-name`
  - `docs/update-readme`
  - `refactor/cleanup-module`

#### Commit Message Conventions
We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:
- `feat: add authentication middleware`
- `fix: resolve hydration mismatch on dashboard`
- `docs: update setup guide in README`
- `chore: bump dependencies`

#### Pull Request (PR) Process
1. **Sync:** Ensure your branch is rebased on the latest `main`.
2. **Lint & Test:** Run all linters, formatting tools, and test suites locally:
   ```bash
   npm run lint
   npm run test
