# Contribution Guide

This guide defines the working standards for this repository in order to maintain consistency, quality, and traceability.

## ♻️ General Workflow

1. **Issue:** Create an issue describing the task or bug (if applicable).
2. **Branch:** Create a branch from `main` following the naming convention.
3. **Code:** Make small and descriptive commits (Conventional Commits).
4. **PR:** Create a Pull Request linking the issue.
5. **Review:** Wait for approval before merging.
6. **Cleanup:** Delete the branch once it has been merged.

## 🪾 Branch Naming Convention

Format: `type/very-brief-description`

| Type | Use | Example |
| :--- | :--- | :--- |
| `feature/` | New features | `feature/move-leg` |
| `fix/` | Bug fixes | `fix/arm-collapse-error` |
| `refactor/` | Improvements without functional changes | `refactor/reorganize-services` |
| `chore/` | Technical tasks (deps, config) | `chore/update-dependencies` |
| `docs/` | Documentation | `docs/improve-docs` |

## ⬆️ Commit Convention

We use **Conventional Commits**.  
* Imperative mood ("add", not "added").
* Maximum ~50 characters in the title.
* No period at the end.

**Structure:**  
`type: short description`

**Allowed types:**
* `feat`: New feature
* `fix`: Bug fix
* `docs`: Documentation
* `style`: Formatting (spaces, commas)
* `refactor`: Refactor without behavior changes
* `test`: Tests
* `chore`: Miscellaneous tasks

**Example:** `feat: add script to move leg`

## 🧹 Maintenance
* Update dependencies regularly.
* Delete obsolete branches after merge.
* Keep the README up to date.
