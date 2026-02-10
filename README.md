# AI Standards & Rules Repository

This repository acts as the **Single Source of Truth** for AI coding agents (Cursor, Copilot, Claude) across our organization.

## How to use in a project

Run the following command in your project root to fetch these rules:

\`\`\`bash
npx rulesync fetch github:YOUR_ORG/THIS_REPO_NAME --path rules/00_stack_rules.md --output rules/00_global_stack.md
npx rulesync fetch github:YOUR_ORG/THIS_REPO_NAME --features subagents,skills
\`\`\`
