# Skills

A collection of reusable agent skills for everyday engineering work.

## Setup

1. Install via skills.sh:

```bash
npx skills@latest add tapanij/skills
```

2. Select the skills you want and the agents to install them on. Done.

## Skills

### `/summarize-session`

Generates a concise summary of what was accomplished in the current conversation — what was built, which files were changed, and key technical decisions made.

### `/verify-documentation`

Reads a documentation file and cross-checks its claims against the actual codebase (file structure, project manifests, source code). Corrects outdated or inaccurate content in-place without adding unnecessary new sections.
