# Obsidian Prompt System

## Purpose

此資料夾存放 Obsidian 知識庫相關的 Agent prompt、知識整理規則、標籤規範與專案串接模板。

Obsidian 的定位是長期知識庫，不是單一專案資料夾。  
每個 project 的 `agent.md` 只負責指定本專案需要使用哪些 MOC、tags、rules，不應該複製整套知識庫規則。

---

## Folder Role

- `06_Prompts/`：Agent prompt 與知識庫操作規則
- `07_Tag_Index/` 或本檔案內的 Tag Index：標籤規範
- `04_MOC/`：主題地圖
- `03_Atomic Notes/`：長期可複用知識
- `02_Literature Notes/`：忠於來源的整理
- `01_Sources/`：原始資料與來源筆記
- `00_Inbox/`：暫存與待整理資料

---

## Core Workflow

資料進入知識庫後，應依照以下流程處理：

1. Intake Agent：接收資料並初步分類
2. Literature Note Agent：整理成忠於來源的文獻筆記
3. Atomic Note Agent：拆成可長期使用的原子筆記
4. Linking Agent：建立相關筆記連結
5. MOC Builder Agent：整理進主題地圖
6. Vault Review Agent：定期檢查孤兒筆記、重複筆記、標籤混亂與知識缺口

---

## Important Principle

Project 是工作現場。  
Obsidian 是知識沉澱層。  
Agent 是整理與連結工具，不是最終判斷者。

任何 AI 產出的內容都必須經過人工確認，才能進入正式知識庫。