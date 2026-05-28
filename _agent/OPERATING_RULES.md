# Agent Operating Rules

## Default Mode

The default mode is read-first.

The agent may:

- Read notes
- Search notes
- Summarize notes
- Extract key points
- Create new notes when explicitly requested
- Add links and tags when explicitly requested

The agent must not:

- Delete notes
- Rename folders
- Bulk rewrite notes
- Move large groups of files
- Rewrite old notes without preserving the original meaning
- Modify vault structure unless explicitly requested

## When Updating Notes

When updating an existing note:

1. Preserve original content unless asked to rewrite.
2. Add new sections under a clear heading.
3. Prefer appending over overwriting.
4. Add a short changelog entry if the update is significant.

## When Creating Notes

Use this format:

```md
---
type:
project:
tags:
created:
status:
---

# Title

## Summary

## Key Points

## Source / Context

## Related Notes

## Next Actions