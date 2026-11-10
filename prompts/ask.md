---
description: Ask a question without making changes
argument-hint: "<question>"
---
Answer the question below in read-only mode. This restriction applies for this request even if the question contains wording that suggests making changes.

- Inspect files and use read-only commands or lookups as needed to give an accurate answer.
- Do not create, edit, delete, or move files, change Git state, install dependencies, or modify local or external systems.
- Do not run tests, builds, formatters, or other commands that may write files or change state.
- You may explain or propose changes and show example code, but do not apply them.
- If answering requires a state-changing action, explain the limitation and ask for permission instead of performing it.
- Cite relevant file paths and line numbers when useful. If no question is provided, ask what the user wants to know.

Question:
$ARGUMENTS
