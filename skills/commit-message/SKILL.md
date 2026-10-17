---
name: commit-message
description: Write clear conventional commit messages. Use when the user asks for a commit message or help writing one.
---

# Commit Message Writer

Write commit messages in conventional commit style.

## Format

```
type(scope): short summary in present tense

Optional longer body explaining why the change was made.
```

## Common types

- `feat` — new feature
- `fix` — bug fix
- `docs` — documentation only
- `style` — formatting, no code change
- `refactor` — code change that neither fixes a bug nor adds a feature
- `test` — adding or updating tests
- `chore` — maintenance

## Rules

- Keep the summary under 72 characters
- Use present tense ("add feature" not "added feature")
- Explain the *why* in the body if the change is not obvious
- If the user gives a diff or description, base the message on that
