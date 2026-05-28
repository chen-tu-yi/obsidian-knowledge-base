# Project Agent Knowledge Base Block Template

## Purpose

此模板用於貼到每個 project 的 `agent.md` 中。  
它的作用是告訴 project agent：

1. Obsidian 知識庫在哪裡。
2. 本 project 應使用哪些 MOC。
3. 本 project 應使用哪些 tags。
4. 產出的長期知識應如何回寫 Obsidian。
5. 哪些內容不能直接寫成知識結論。

---

## Template

請將以下區塊貼到 project 的 `agent.md`：

```markdown
## Knowledge Base Access

### Obsidian Vault Location

`C:\Knowledge_Base\Obsidian_Vault\`

### Required MOC

- [[MOC - ]]
- [[MOC - ]]
- [[MOC - ]]

### Required Knowledge Tags

- #domain/
- #method/
- #project/

### Optional Knowledge Tags

- #source/
- #status/evergreen

---

## Knowledge Usage Rules

1. 優先使用 Required MOC 中的知識。
2. 若 MOC 不足，再搜尋 Required Knowledge Tags。
3. Optional Knowledge Tags 只在需要補充時使用。
4. 不得把未驗證資料當成事實。
5. 若引用 Obsidian 筆記，必須標示筆記名稱。
6. 若產生可長期複用的知識，請整理成 Obsidian Markdown 草稿。
7. 新產出的知識預設標記為 `#status/needs_review`。
8. 不得直接修改 Obsidian Vault，除非使用者明確要求。
9. 若內容只對本 project 有效，留在 project output，不必進入 Atomic Notes。
10. 若內容能跨 project 重複使用，才建議沉澱進 Obsidian。

---

## Knowledge Extraction Output

本 project 的最終輸出需包含：

### 1. Project Output

當前 project 直接需要的成果。

### 2. Key Findings

本次任務得到的重要發現。

### 3. Knowledge Extraction

可沉澱進 Obsidian 的長期知識。

### 4. Suggested Obsidian Notes

建議新增或更新的筆記：

- [[...]]

### 5. Suggested MOC Updates

建議更新的 MOC：

- [[MOC - ]]

### 6. Open Questions

仍需查證或補強的問題：

- [ ] 
```

---

## Example: Trading Project

```markdown
## Knowledge Base Access

### Obsidian Vault Location

`C:\Knowledge_Base\Obsidian_Vault\`

### Required MOC

- [[MOC - Trading Strategy]]
- [[MOC - Risk Management]]
- [[MOC - Backtesting]]

### Required Knowledge Tags

- #domain/trading
- #method/breakout_trading
- #method/position_sizing
- #method/risk_management
- #method/backtesting
- #project/trading_strategy

### Optional Knowledge Tags

- #domain/quant_finance
- #method/statistical_modeling
- #source/video
- #source/book
```

---

## Example: Resume Project

```markdown
## Knowledge Base Access

### Obsidian Vault Location

`C:\Knowledge_Base\Obsidian_Vault\`

### Required MOC

- [[MOC - Resume and Career]]
- [[MOC - Quant Finance]]
- [[MOC - Interview Story Bank]]

### Required Knowledge Tags

- #domain/resume
- #domain/job_application
- #domain/quant_finance
- #method/star_resume
- #method/jd_mapping
- #method/ats_keywords
- #project/job_application

### Optional Knowledge Tags

- #domain/equity_research
- #domain/risk_management
- #source/personal_experience
```

---

## Example: Software Project

```markdown
## Knowledge Base Access

### Obsidian Vault Location

`C:\Knowledge_Base\Obsidian_Vault\`

### Required MOC

- [[MOC - Software Engineering]]
- [[MOC - Agent Workflow]]
- [[MOC - Project Architecture]]

### Required Knowledge Tags

- #domain/software_engineering
- #domain/agent_workflow
- #method/system_design
- #method/debugging
- #method/testing
- #project/software_dev

### Optional Knowledge Tags

- #domain/python
- #domain/typescript
- #method/refactoring
- #method/api_design
```