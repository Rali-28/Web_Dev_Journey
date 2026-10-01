# Git Commit Best Practices

One commit = one complete, related change. Keep it small, working, and easy to understand.

## Before committing

- [ ] Check changes: `git status` and `git diff`.
- [ ] Stage only relevant files: `git add <file>`.
- [ ] Review the commit: `git diff --staged`.
- [ ] Test or preview the change.
- [ ] Confirm no secrets, `.env` files, or accidental files are included.

## Commit-message format

```text
type(optional scope): short description

optional body explaining why
```

Examples:

```text
feat: add contact form
fix(nav): correct mobile menu links
docs: update setup instructions
```

Write the summary in lowercase, use an action verb, and avoid a period at the end. A scope is optional. Use `!` or a `BREAKING CHANGE:` footer only for a breaking change.

## Conventional Commit types

`feat` and `fix` are defined by the Conventional Commits specification. The rest below are widely used conventions; teams may add their own.

| Type | Use for |
| --- | --- |
| `feat` | A new user-facing feature |
| `fix` | A bug correction |
| `docs` | Documentation only |
| `style` | Formatting only; no code behavior change |
| `refactor` | Code restructuring without a feature or bug fix |
| `perf` | Performance improvement |
| `test` | Adding or correcting tests |
| `build` | Build system, dependencies, or packaging changes |
| `ci` | Continuous-integration configuration or scripts |
| `chore` | Maintenance work that fits no other type |
| `revert` | Reverting an earlier commit |

## Quick rules

- [ ] Use a clear message: `Add accessible contact form`, not `update`.
- [ ] Do not mix unrelated changes in one commit.
- [ ] Commit regularly after small, finished tasks.
- [ ] Prefer several focused commits over one large commit.
- [ ] Read your history with `git log --oneline`; it should tell the story of the project.
