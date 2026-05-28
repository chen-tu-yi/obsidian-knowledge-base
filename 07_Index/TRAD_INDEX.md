---
type: project_index
project: trad
status: needs_review
tags:
  - project/trad
  - domain/trading
  - domain/quant_finance
  - domain/risk_management
  - method/backtesting
  - status/needs_review
---

# TRAD_INDEX

## Purpose

This index connects the Obsidian knowledge base to the `trad` repository.

Use it as the first project-level navigation note for trading-system research, backtest assumptions, strategy sources, and agent workflow context.

## Repository

```text
GitHub: chen-tu-yi/trad
```

## Required Repo Files

Read these before using KB notes to modify the repo:

```text
agent/AGENTS.md
agent/workflow/agent.md
agent/workflow/agent_skill.md
agent/workflow/backtest_audit_checklist.md
agent/workflow/development_roadmap.md
agent/workflow/knowledge_base_indexing.md
README.md
```

## Required Vault Files

```text
AGENTS.md
00_INDEX.md
_agent/START_HERE.md
_agent/OPERATING_RULES.md
_agent/ROUTING.md
06_Prompts/Knowledge_Tag_Index.md
05_Projects/trad/PROJECT_CONTEXT.md
05_Projects/trad/agent.md
```

## Strategy Research Inbox

Use this section to link source notes or literature notes related to trader strategies.

- Qullamaggie / Kristjan Kullamägi strategy notes: pending
- Mark Minervini SEPA / VCP notes: pending
- Umar Ashraf process / journaling notes: pending
- Larry Williams short-term futures notes: pending
- Ross Cameron day-trading momentum notes: pending
- Alex Temiz first-red-day notes: pending
- Korean trader Flight notes: pending
- MACD divergence notes: pending
- Bit浪浪 crypto cycle notes: pending

## Repo-Side Research Ticket Template

Before implementing any strategy idea from the vault, convert it into:

```text
Hypothesis:
Source notes:
Market:
Timeframe:
Signal definition:
Execution assumption:
Risk model:
Expected outputs:
Validation plan:
Failure modes:
Evidence quality:
Decision:
```

## Current Known Direction

- BTC 4-hour research first.
- Rule-based trend-following before ML.
- Backtest credibility before return maximization.
- Paper trading before live trading.

## Knowledge Gaps

- [ ] Add source notes for major trader strategy references.
- [ ] Add a reusable backtest assumption checklist note.
- [ ] Add a strategy research ticket note template.
- [ ] Add a risk-control checklist note.
- [ ] Link generated source notes back to this index.

## Changelog

- Created initial project index for `trad` knowledge-base routing.
