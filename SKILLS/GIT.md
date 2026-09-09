# Git Skill

## Pre-change
- `git status`
- current branch
- recent history
- repository contribution rules

## During change
Keep scope focused. Avoid unrelated formatting churn.

## Before commit
- inspect `git diff`
- inspect `git diff --cached`
- scan for secrets
- run applicable tests/checks

## Commit
Use a concise Conventional Commit message.

## After commit
Verify:
- commit hash
- branch
- status

## Push
Push only when the approved plan calls for it or repository automation explicitly requires it. Verify the actual push result.

Never claim a commit/push succeeded from intent alone.
