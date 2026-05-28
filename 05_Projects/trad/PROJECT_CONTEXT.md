---
type: project_context
project: trad
status: needs_review
tags:
  - project/trad
  - domain/trading
  - domain/quant_finance
  - method/backtesting
  - status/needs_review
---

# trad Project Context

## Project Purpose

`trad` is a systematic trading research repository focused on building a credible BTC 4-hour rule-based trend-following research, backtest, audit, and paper-trading framework.

The project is not a live-trading-first bot. Its priority is credible research and controlled validation.

## Repository Location

```text
GitHub: chen-tu-yi/trad
Local expected path: C:/local_file/trad or project workspace path
```

## Agent Should Read First

Inside the `trad` repo:

```text
agent/AGENTS.md
agent/workflow/agent.md
agent/workflow/agent_skill.md
agent/workflow/backtest_audit_checklist.md
agent/workflow/development_roadmap.md
agent/workflow/knowledge_base_indexing.md
README.md
```

Inside this Obsidian vault:

```text
AGENTS.md
00_INDEX.md
_agent/START_HERE.md
_agent/ROUTING.md
06_Prompts/Knowledge_Tag_Index.md
07_Index/TRAD_INDEX.md
05_Projects/trad/agent.md
```

## Current Strategy Context

Current research direction:

- Plan A: N-pattern / swing breakout with ADX trend-strength filter, long SMA trend filter, and large-candle filter.
- Plan B: moving-average pullback with ATR-based trailing stop.
- Market: BTC / USDT or BTC perpetual-like OHLCV.
- Timeframe: 4-hour bars.

The 4-hour timeframe is an informed research choice, not final proof of robustness.

## Current Development Priorities

1. Repository executability.
2. Backtest correctness.
3. No-look-ahead guarantees.
4. Mark-to-market equity and drawdown.
5. Explicit fee and slippage assumptions.
6. Trade log and metrics export.
7. Robustness testing.
8. Paper-trading reliability.
9. Live-trading safety.
10. Optional ML meta-labeling.

## Knowledge Base Role

This Obsidian project folder should store:

- Research decisions
- Strategy hypotheses
- External trader/source notes
- Backtest interpretation notes
- Risk-control checklists
- Agent prompts and routing notes
- Long-term lessons learned

It should not store generated reports that belong in the repo `reports/` folder.

## Rule

If a knowledge-base note conflicts with the `trad` repo workflow, the repo workflow wins.

If the conflict is important, document it under `07_Index/TRAD_INDEX.md` or a project decision note.
