# Contributing to Vencore

Thank you for your interest in contributing to Vencore! We welcome code contributions, documentation updates, bug reports, and feature suggestions.

---

## 1. Development Workflow Rule

To keep our Discord task tracking and GitHub commit histories clean, we enforce a strict workflow:

1. **Find or Open an Issue**: Before writing code, ensure an issue exists in the repository. If not, open one (e.g. via our direct update helpers).
2. **Create a Feature Branch**: Branch off `main` using descriptive naming:
   * Features: `feature/short-description`
   * Bug Fixes: `bugfix/short-description`
   * Chores/Maintenance: `chore/short-description`
3. **Commit Messages**: Reference the issue or tissue tag in your commit messages:
   * *Example*: `feat: implement user login check (closes #12)` or `fix(cli): rename log channel fields (ref BOT-15)`
4. **Submit a Pull Request (PR)**: Target the `main` branch. Fill out the PR template completely.
5. **Code Review & Merge**: Once reviews pass and automated tests succeed, maintainers will merge the branch.

---

## 2. Coding Guidelines

We enforce the following standards across all repositories in the Vencore organization:

* **Language**: TypeScript (strict mode enabled). Write clean, type-safe interfaces rather than resorting to `any`.
* **Code Formatting**: We use ESLint and Prettier. Run formatting checks before committing.
* **Documentation**: Document public APIs, hooks, and complex functions with TSDoc comments. Keep `README.md` and `CHANGELOG.md` files updated.
* **Testing**: Write unit tests for new features and core utilities. Ensure all existing tests pass before opening a PR.

---

## 3. GitHub Label Reference

We use standard issue/PR labels to organize tasks:
* `bug`: Something isn't working as expected.
* `enhancement`: New feature or improvement proposal.
* `task`: Chores, refactoring, or infrastructure updates.
* `triage`: New issues awaiting review.
* `dependencies`: Automatic dependency updates.
