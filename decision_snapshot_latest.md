# Decision Snapshot V1

更新時間：2026-09-24T23:04:59.589714+08:00
Session：POSTMARKET
Report Date：2026-09-24
Latest Market Trade Date：2026-09-24
Freshness：PASS

## TAIEX

- Direction：57/100
- Confidence：62/100
- Regime：Neutral / Range
- Action：中性觀望
- Event Risk：0/100

### Market Structure

- Market Health：FRAGILE (44.8)
- Breadth：41.4/100；BROAD SELL-OFF
- Participation：MIXED (43.2)
- Concentration：N/A
- Rotation / Risk Appetite：MIXED / 64.1
- Breadth Divergence：N/A (INSUFFICIENT_HISTORY)

### Active ETF Data

- Data Quality：PARTIAL
- Holdings / Shares / Units Coverage：6.9% / 100.0% / 3.45%
- Diagnostic only；本階段不產生交易訊號。

## 台積電（2330）

- Price：2475
- Direction：68/100
- Confidence：59/100
- Decision：偏多但等待確認
- Execution：WAIT FOR BETTER PRICE
- Chase Risk：46/100
- R/R Gate：BLOCK

### Entry

- Entry Zone 1：2465 ～ 2475
- Entry Zone 2：2425 ～ 2445
- Breakout：2515

### Exit

- Hard Stop：2405
- TP1：2510
- TP2：2555
- TP1 Protection：2480
- TP2 Protection：2515

### Position

- Recommended Current Position：0%
- Planned Initial Position：15%
- Maximum Position：40%
- Risk Budget：0.5%

### Institutional

- Stock Institutional Score：44/100
- Individual Flow Score：55/100
- Data Quality：FULL
- 外資 5D：6855 張
- 三大法人 5D：8242 張
- 外資 20D：-10490 張
- 三大法人 20D：-10199 張

## 聯電（2303）

- Price：154
- Direction：63/100
- Confidence：59/100
- Decision：偏多但等待確認
- Execution：WAIT FOR STABILIZATION
- Chase Risk：78/100
- R/R Gate：POOR

### Corporate Action

- Corporate Event：海外第七次無擔保轉換公司債／擴產
- Event Stage：D+21 CONFIRMATION
- Post-Event Score：67/100
- Relative Strength：IMPROVING
- Institutional Reaction：-44180923.0
- Volume Reaction：NORMAL
- Event Status：RECOVERY
- Add Position：BLOCKED
- Recovery Trigger：141.72
- Structural Failure：120.0
- Event Review：D+10

### Entry

- Entry Zone 1：148 ～ 151
- Entry Zone 2：140 ～ 143
- Breakout：165

### Exit

- Hard Stop：138.5
- TP1：164.5
- TP2：168.5
- TP1 Protection：156.5
- TP2 Protection：164.5

### Position

- Recommended Current Position：0%
- Planned Initial Position：5%
- Maximum Position：15%
- Risk Budget：0.5%

### Institutional

- Stock Institutional Score：53/100
- Individual Flow Score：67/100
- Data Quality：FULL
- 外資 5D：27678 張
- 三大法人 5D：57140 張
- 外資 20D：54739 張
- 三大法人 20D：192852 張

## Validation

- Status：OK
- All required snapshot fields parsed successfully.

## Snapshot Policy

- Snapshot 只整合既有模型輸出，不重新計算 Direction 或 Confidence；Execution 可顯示 Corporate Action Layer 的 override。
- Snapshot 用於盤前 / 盤後決策介面，不取代原始完整報告。
- 模型公式、詳細權重與內部計算邏輯不輸出至精簡 Snapshot。
- Private repository 仍為完整模型的唯一主要來源。
