# Skills — Antigravity / ECC Skill Library

A curated collection of **280+ skills** and **68 agent personas** for use with Antigravity IDE and [ECC (Everything Claude Code)](https://github.com/affaan-m/ECC).

## Structure

```
Skills/
├── <skill-name>/          # Each folder is a discoverable skill
│   └── SKILL.md           # Skill instructions with YAML frontmatter
├── agents/                # 68 agent persona markdown files
├── .agents-skills/        # ECC curated "daily tier" skill subset
└── .agents-plugins/       # ECC plugin marketplace registry
```

## How to Use in Antigravity

Add to `~/.gemini/config/skills.json`:

```json
{
  "entries": [
    { "path": "/path/to/this/Skills" }
  ]
}
```

Or drop any skill folder into your project's `.agents/skills/` for project-scoped use.

## Source

Sourced from [affaan-m/ECC](https://github.com/affaan-m/ECC).
