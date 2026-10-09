# claude-skill-library

Shared Claude skills for Apolix. Department-specific skills live in the `skills-*` repos of this organization.

## Naming convention

Every skill is one folder at the root of the repo:

```
<skill-name>/
├── SKILL.md      required, exactly this name (uppercase)
├── icon.svg      optional, shown on the skills website (icon.png also works)
└── ...           optional extra files the skill references (scripts, templates)
```

- **Folder name** = the skill's `name`: lowercase letters, numbers and hyphens only (e.g. `commit-drama`, not `Sophias Skill`). Max 64 characters.
- **`SKILL.md`** starts with frontmatter:

  ```markdown
  ---
  name: commit-drama
  description: What the skill does and when Claude should use it. Max 1024 characters.
  ---
  ```

- The `description` is shown on the skills website and is what Claude uses to decide when to load the skill, so say both *what* and *when*.

## Skills in this repo

| Skill | What it does |
|---|---|
| [commit-drama](commit-drama/SKILL.md) | Commit messages as movie-trailer narration, with a real summary line |
| [smalltalk](smalltalk/SKILL.md) | Light, friendly small talk |
