---
name: generate-changelog
description: Generate a structured CHANGELOG.md from git history
---

When the user asks to generate a changelog, run:

```bash
bash changelog.sh [REPO_PATH]
```

This finds commits since the last git tag, categorizes them into Added/Fixed/Changed/Removed, and outputs a structured CHANGELOG.md.
