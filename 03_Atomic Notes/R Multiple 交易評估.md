---
type: atomic_note
topic: r_multiple_trade_evaluation
domain: trading_strategy
method: performance_measurement
status: needs_review
source: "[[交易員策略可信度與交易系統框架]]"
created: 2026-05-29
tags:
  - domain/trading_strategy
  - method/performance_measurement
  - status/needs_review
---

# R Multiple 交易評估

## 一句話定義

R Multiple 交易評估，是把每筆交易結果換算成相對於初始風險的倍數，用來衡量策略品質與執行品質。

## 核心概念

文章指出交易不是單純勝率遊戲，而是 R multiple 遊戲。低勝率策略如果平均獲利遠大於平均虧損，仍可能賺錢；高勝率策略若小賺大賠，長期仍可能虧損。

## 使用條件

- 每筆交易進場前已定義初始停損。
- 能計算每筆交易的 planned risk。
- 能記錄實際出場後的 realized R。

## 適用場景

- 交易日誌。
- 回測報告。
- 策略比較。
- 檢查是否提早停利、擴大停損或違反計畫。

## 不適用場景

- 沒有固定風險定義的隨機交易。
- 不記錄停損位置，只記錄盈虧金額。

## 常見誤解

R multiple 不是只看單筆大賺，而是看一組交易的分布，例如平均贏家、平均輸家、最大虧損、連虧與 setup 表現。

## 例子

若一筆交易初始風險是 100 美元，最後獲利 500 美元，結果是 +5R。若最後虧損 100 美元，結果是 -1R。

## 反例

一筆交易獲利 1,000 美元看似很好，但若初始風險是 2,000 美元，實際只有 +0.5R，策略延伸能力可能不足。

## 我的理解

R multiple 能把不同標的、不同價格與不同倉位的交易放在同一把尺上比較。

## AI 補充

> AI 補充：交易日誌至少應記錄 setup、planned R、realized R、是否依計畫進出場、是否違反禁止條件。

## Related Notes

- [[不對稱交易機會]]
- [[交易 Playbook]]

## Belongs to MOC

- [[MOC - Trading Strategy]]

## Source

- [[交易員策略可信度與交易系統框架]]

## 待確認

- [ ] 定義回測報告中的 R multiple 欄位。
- [ ] 建立 planned R 與 realized R 的紀錄格式。
