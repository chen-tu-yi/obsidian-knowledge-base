---
type: atomic_note
topic: trading_playbook
domain: trading_strategy
method: process_design
status: needs_review
source: "[[交易員策略可信度與交易系統框架]]"
created: 2026-05-29
tags:
  - domain/trading_strategy
  - method/process_design
  - status/needs_review
---

# 交易 Playbook

## 一句話定義

交易 Playbook 是把一種 setup 的市場條件、進出場、風控、禁止條件與復盤方式寫成可重複執行的規則。

## 核心概念

文章引用 Umar Ashraf / TradeZella 的流程觀點，強調新手不應只追求賺錢，而應先建立可重複流程。Playbook 的價值在於把策略從模糊感覺變成可記錄、可檢查、可改進的作業流程。

## 使用條件

- 已選定一種 setup。
- 能明確描述進場條件、停損與出場規則。
- 願意記錄每筆交易是否符合 playbook。

## 適用場景

- 將 Qullamaggie Breakout、EP、VCP、Bull Flag 等策略標準化。
- 建立交易日誌欄位。
- 區分策略問題與執行問題。

## 不適用場景

- 只想快速下單，不願意記錄條件與結果。
- 策略仍停留在「看到感覺不錯」的主觀描述。

## 常見誤解

寫交易日誌不會自動帶來獲利。Playbook 必須包含具體 setup 與風險規則，否則只是事後心得。

## 例子

一個 Breakout Playbook 可以包含：市場環境、強勢股篩選、整理結構、ORH 觸發、當日低點停損、3 到 5 天部分出場、10 日或 20 日均線追蹤。

## 反例

「今天感覺很強所以買，跌了再看」不是 playbook，因為沒有觸發條件、停損與失效規則。

## 我的理解

Playbook 是交易研究與實盤執行之間的橋，沒有它很難知道自己是在執行策略還是在臨場反應。

## AI 補充

> AI 補充：每個 playbook 應該同時有「必要條件」與「禁止條件」，避免只寫進場訊號。

## Related Notes

- [[R Multiple 交易評估]]
- [[交易策略來源可信度分級]]

## Belongs to MOC

- [[MOC - Trading Strategy]]

## Source

- [[交易員策略可信度與交易系統框架]]

## 待確認

- [ ] 建立第一個具體 setup playbook 模板。
- [ ] 決定交易日誌欄位。
