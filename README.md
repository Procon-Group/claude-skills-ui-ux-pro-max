# UI UX Pro Max (Claude Code skill)

The [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) design skill, installed for Claude Code.
Vendored from upstream v2.15.0 (commit `56ea9cf174ed86786187daa9de0e6247cb0747e4`) under the MIT license — see [LICENSE](LICENSE).

## What's here

`.claude/skills/ui-ux-pro-max/` — searchable UI styles, color palettes, font pairings, UX guidelines,
chart types and stack-specific guidance, plus a design-system generator.

Claude Code picks the skill up automatically when it runs in this repo. To use it in another project,
copy `.claude/skills/ui-ux-pro-max` into that project's `.claude/skills/` (or `~/.claude/skills/` for all projects).

## Manual search

```bash
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "fintech dashboard" --domain color
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "fleet tracking SaaS" --design-system
```

## Updating

Re-copy `.claude/skills/ui-ux-pro-max` from the latest upstream release.
