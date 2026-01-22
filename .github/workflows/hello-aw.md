---
name: Hello, Agentic Workflows
on:
  workflow_dispatch:

permissions:
  contents: read
  issues: read

engine: claude

safe-outputs:
  create-issue:
    title-prefix: "[agentic] "
    max: 1
---

1. Create a new GitHub issue in this repository.
2. Set the title to "Agentic Workflows smoke test".
3. In the issue body, write a short greeting and include today's date in YYYY-MM-DD format.
