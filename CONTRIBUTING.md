# Contributing Guide

## 🌱 Branching
- `main` = production
- `develop` = integration branch
- Feature branches: `feature/<name>`
- Bugfix branches: `bugfix/<name>`

## 📝 Commit Messages
Follow **Conventional Commits**:
- `feat:` → new feature
- `fix:` → bug fix
- `docs:` → docs only
- `style:` → code style (no logic changes)
- `refactor:` → code refactor (no feature/bug)
- `test:` → add/fix tests
- `chore:` → maintenance

### Examples
- `feat(auth): add password hashing`
- `fix(ui): correct button alignment on mobile`
- `docs: update setup steps in README`

## 🚑 Urgent Fixes
- Commit quickly with context:  
  `fix(auth): hotfix login crash (urgent)`
- Add a follow-up task in TODO.md for proper cleanup.

## 🔄 Workflow
1. Pick a task from **TODO.md**.
2. Create a branch (`feature/...` or `bugfix/...`).
3. Commit small, logical changes.
4. Open a PR → review → merge into `develop`.
5. Only merge into `main` when release-ready.

## ✅ Code Style
- Use clear names for variables & functions.
- Add docstrings for non-obvious logic.
- Comment *why*, not *what*.

