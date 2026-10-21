# 🌿 Git Lab 02 — Branching, Merging & Pull Requests

Git lab from the **ITI .NET track** (March 2026) about working with branches — the same workflow I later used with my team on the [Vantio](https://github.com/Mohamed-Elhosinii/Vantio-Backend) graduation project.

## What I practiced
- Creating branches: `master`, `dev`, `test`
- Committing different work on each branch (`file-dev.txt`, `file-test.txt`)
- Opening a **Pull Request** on GitHub and merging `test` into `master` (PR #1)
- Merging remote changes and pushing (`git merge`, `git pull`, `git push`)

```bash
git branch dev
git branch test
git switch dev     # work + commit on dev
git switch test    # work + commit on test
git push -u origin dev test
# then: Pull Request on GitHub  →  merge test into master
git switch master
git pull
```

## Branches
| Branch | Purpose |
|---|---|
| `master` | Main branch |
| `dev` | Development work |
| `test` | Testing work — merged into `master` with a Pull Request |

⬅️ [Lab01](https://github.com/Mohamed-Elhosinii/Lab01) · [Lab-01-part-02](https://github.com/Mohamed-Elhosinii/Lab-01-part-02)
