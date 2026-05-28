# AGENTS.md

## Purpose

This file is the root instruction file for agents working inside this Obsidian knowledge base.

The vault is a knowledge layer. Project repositories remain the execution layer.

## Mandatory Startup Order

When an agent enters this vault, read in this order:

1. `_agent/START_HERE.md`
2. `_agent/OPERATING_RULES.md`
3. `_agent/ROUTING.md`
4. `06_Prompts/00_README.md`
5. `06_Prompts/Knowledge_Tag_Index.md`
6. Relevant project context under `05_Projects/`
7. Relevant MOC under `04_MOC/`

If a file is missing, report it and continue with available files.

## Core Rule

Do not treat this vault as the place where production work is executed.

- Use project repos for source code, tests, configs, and runtime artifacts.
- Use this vault for source notes, research context, decisions, prompts, MOCs, and long-term reusable knowledge.

## Agent Behavior

Default mode is read-first.

Agents may:

- Search notes
- Summarize notes
- Extract key points
- Draft new notes when requested
- Add links and tags when requested
- Update project index files when requested

Agents must not:

- Delete notes
- Rename folders
- Bulk rewrite the vault
- Move large groups of files
- Rewrite old notes without preserving their meaning
- Promote unreviewed notes to evergreen status

## Routing

Use `_agent/ROUTING.md` to decide what to read for each task.

For the `trad` repository, start with:

- `05_Projects/trad/PROJECT_CONTEXT.md`
- `05_Projects/trad/agent.md`
- `07_Index/TRAD_INDEX.md`
- `06_Prompts/Knowledge_Tag_Index.md`

## Output Contract

When an agent uses this vault, report:

- Entry files read
- Relevant notes read
- Tags searched
- Notes created or updated
- Project repo assumptions imported from the vault
- Items that still need human review
