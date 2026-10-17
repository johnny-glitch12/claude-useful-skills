---
name: code-reviewer
description: Review code for bugs, security issues, style problems, and improvements. Use when the user asks to review code, check a pull request, or look for problems in code.
---

# Code Reviewer

When asked to review code, follow this process:

1. **Understand the goal** — What is this code supposed to do?
2. **Check correctness** — Does it actually do that? Look for logic errors, off-by-one mistakes, edge cases.
3. **Check safety** — Any security issues (injection, secrets, unsafe input handling)?
4. **Check style & readability** — Is it clear? Are names good? Is it overly complex?
5. **Suggest improvements** — Be specific. Show the better version when possible.

## Output format

- Start with a short summary (1-2 sentences)
- List issues by severity: Critical / Warning / Suggestion
- For each issue, explain why it matters and how to fix it
- End with any positive notes about the code

Be direct and helpful. Do not rewrite the entire file unless asked.
