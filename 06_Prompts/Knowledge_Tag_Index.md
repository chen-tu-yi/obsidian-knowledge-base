# Knowledge Tag Index

## Purpose

此文件定義 Obsidian 知識庫可使用的標籤系統。  
所有 Agent 與 project 的 `agent.md` 都應遵守此 tag 規範。

Tag 的用途是篩選，不是主要結構。  
主要結構應由 MOC 負責。

---

## Tag Naming Rules

使用層級式 tag：

```text
#domain/xxx
#method/xxx
#project/xxx
#source/xxx
#status/xxx
#asset/xxx
```

不要使用：

```text
#finance
#note
#study
#important
#todo
#good
```

---

## Domain Tags

### Finance

* #domain/quant_finance
* #domain/equity_research
* #domain/risk_management
* #domain/portfolio_management
* #domain/fixed_income
* #domain/credit_risk
* #domain/valuation
* #domain/trading
* #domain/personal_finance

### Career

* #domain/resume
* #domain/job_application
* #domain/interview
* #domain/networking
* #domain/career_strategy

### Software

* #domain/software_engineering
* #domain/python
* #domain/typescript
* #domain/flutter
* #domain/ai_ml
* #domain/agent_workflow
* #domain/system_design
* #domain/data_engineering

### Learning

* #domain/learning_system
* #domain/note_taking
* #domain/knowledge_management
* #domain/research_method

### Personal Projects

* #domain/content_creation
* #domain/startup
* #domain/product_design
* #domain/ui_ux

---

## Method Tags

### Research Methods

* #method/data_analysis
* #method/statistical_modeling
* #method/time_series
* #method/regression
* #method/classification
* #method/model_validation
* #method/scenario_analysis
* #method/stress_testing

### Finance Methods

* #method/dcf
* #method/comparable_analysis
* #method/cash_flow_modeling
* #method/portfolio_construction
* #method/risk_return_modeling
* #method/derivatives_hedging
* #method/credit_modeling

### Trading Methods

* #method/breakout_trading
* #method/trend_following
* #method/position_sizing
* #method/stop_loss
* #method/risk_management
* #method/backtesting
* #method/trade_review
* #method/market_regime_filter

### Career Methods

* #method/star_resume
* #method/jd_mapping
* #method/ats_keywords
* #method/interview_story
* #method/cover_letter_mapping

### Agent Methods

* #method/prompt_engineering
* #method/workflow_design
* #method/context_management
* #method/task_decomposition
* #method/knowledge_extraction
* #method/moc_building

### Software Methods

* #method/debugging
* #method/testing
* #method/refactoring
* #method/api_design
* #method/database_design
* #method/frontend_architecture
* #method/backend_architecture

---

## Project Tags

* #project/trading_strategy
* #project/resume_optimization
* #project/job_application
* #project/quant_research
* #project/equity_research
* #project/software_dev
* #project/obsidian_kb
* #project/content_creation
* #project/startup_idea
* #project/personal_finance

---

## Source Tags

* #source/book
* #source/pdf
* #source/video
* #source/article
* #source/course
* #source/podcast
* #source/personal_experience
* #source/project_output
* #source/official_document
* #source/academic_paper
* #source/company_filing
* #source/social_media

---

## Status Tags

* #status/raw
* #status/needs_review
* #status/evergreen
* #status/archived
* #status/deprecated
* #status/actionable
* #status/reference_only

---

## Asset Tags

* #asset/template
* #asset/prompt
* #asset/framework
* #asset/checklist
* #asset/example
* #asset/case_study
* #asset/code_snippet
* #asset/research_note

---

## Tag Use Examples

### Trading Atomic Note

```yaml
tags:
  - domain/trading
  - method/position_sizing
  - method/risk_management
  - status/needs_review
```

### Resume Project Note

```yaml
tags:
  - domain/resume
  - method/jd_mapping
  - method/star_resume
  - project/job_application
  - status/evergreen
```

### Python Debugging Note

```yaml
tags:
  - domain/python
  - method/debugging
  - method/testing
  - status/evergreen
```

---

## New Tag Rule

若需要新增 tag，必須先確認：

1. 是否已有相近 tag。
2. 是否能長期重複使用。
3. 是否符合層級格式。
4. 是否值得放進 Knowledge Tag Index。

新 tag 預設不可直接加入正式筆記，應先標記為：

```text
#status/needs_review
```