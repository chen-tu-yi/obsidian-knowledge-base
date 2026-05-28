---
type: moc
topic: agent_workflow
status: needs_review
tags:
  - domain/agent_workflow
  - method/workflow_design
  - project/obsidian_kb
  - status/needs_review
---

# MOC - Agent Workflow

## Purpose

This MOC organizes agent operating rules, prompt workflows, context routing, and knowledge extraction procedures.

---

## Core Rules

- [[Obsidian_Knowledge_Base_Rules]]
- [[Project_Agent_KB_Block_Template]]
- [[Knowledge_Tag_Index]]

---

## Agent Workflow Prompts

- [[Intake_Agent]]
- [[Literature_Note_Agent]]
- [[Atomic_Note_Agent]]
- [[Linking_Agent]]
- [[MOC_Builder_Agent]]
- [[Vault_Review_Agent]]

---

## Operating Documents

- [[START_HERE]]
- [[OPERATING_RULES]]
- [[ROUTING]]

---

## Common Use Cases

### Process a new article

1. Add source to `00_Inbox/`.
2. Run `KB - Process Active Note`.
3. Review generated notes.
4. Move accepted notes into `02_Literature Notes/` and `03_Atomic Notes/`.
5. Update relevant MOC.

### Convert project output into knowledge

1. Review `05_Projects/[project]/OUTPUT.md`.
2. Extract reusable ideas.
3. Create Atomic Notes.
4. Link them back to the original project.

---

## Knowledge Gaps

- [ ] Build command-specific prompt notes for Copilot.
- [ ] Test full article-to-atomic-note flow.
- [ ] Add examples of good and bad agent outputs.
