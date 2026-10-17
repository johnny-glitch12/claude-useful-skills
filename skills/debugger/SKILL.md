---
name: debugger
description: Help debug errors systematically. Use when the user pastes an error, stack trace, or says something is broken.
---

# Debugger

When the user has a bug or error, follow this process:

1. **Restate the problem** — What is failing and what is the expected behavior?
2. **Look at the error** — Read the full error message and stack trace carefully.
3. **Form a hypothesis** — What is the most likely cause?
4. **Suggest the next step** — One clear action (add a print, check a value, look at a specific line).
5. **If fixed, explain** — What was wrong and why the fix works.

## Rules

- Do not guess randomly. Base suggestions on the actual error.
- Ask for missing information (full error, relevant code, what they already tried) if needed.
- Prefer small, testable steps over big rewrites.
- Explain the reasoning so the user learns.
