# Decision Snapshot V1

更新時間：2026-09-23T22:29:15.400546+08:00
Session：POSTMARKET
Report Date：2026-09-23
Latest Market Trade Date：2026-09-23
Freshness：PASS

## TAIEX

- Direction：71/100
- Confidence：62/100
- Regime：Risk-on Bias
- Action：偏多但控制部位
- Event Risk：0/100

### Market Structure

- Market Health：FRAGILE (42.8)
- Breadth：40.8/100；NARROW RALLY / WARNING
- Participation：MIXED (43.7)
- Concentration：N/A
- Rotation / Risk Appetite：MIXED / 62.3
- Breadth Divergence：N/A (INSUFFICIENT_HISTORY)

### Active ETF Data

- Data Quality：PARTIAL
- Holdings / Shares / Units Coverage：3.45% / 100.0% / 0.0%
- Diagnostic only；本階段不產生交易訊號。

## 台積電（2330）

- Price：2500
- Direction：79/100
- Confidence：80/100
- Decision：偏多
- Execution：INVALID SETUP / NO TRADE
- Chase Risk：66/100
- R/R Gate：BLOCK

### Entry

- Entry Zone 1：2455 ～ 2470
- Entry Zone 2：2420 ～ 2440
- Breakout：2510

### Exit

- Hard Stop：2420
- TP1：2505
- TP2：2550
- TP1 Protection：2475
- TP2 Protection：2510

### Position

- Recommended Current Position：0%
- Planned Initial Position：10%
- Maximum Position：20%
- Risk Budget：1%

### Institutional

- Stock Institutional Score：74/100
- Individual Flow Score：75/100
- Data Quality：FULL
- 外資 5D：16317 張
- 三大法人 5D：19199 張
- 外資 20D：-1321 張
- 三大法人 20D：-146 張

## 聯電（2303）

- Price：160
- Direction：69/100
- Confidence：60/100
- Decision：偏多但等待確認
- Execution：WAIT FOR STABILIZATION
- Chase Risk：100/100
- R/R Gate：BLOCK

### Corporate Action

- Corporate Event：海外第七次無擔保轉換公司債／擴產
- Event Stage：D+20 CONFIRMATION
- Post-Event Score：67/100
- Relative Strength：IMPROVING
- Institutional Reaction：-10134633.0
- Volume Reaction：NORMAL
- Event Status：RECOVERY
- Add Position：BLOCKED
- Recovery Trigger：139.95
- Structural Failure：117.0
- Event Review：D+10

### Entry

- Entry Zone 1：154.5 ～ 157
- Entry Zone 2：147 ～ 150
- Breakout：165

### Exit

- Hard Stop：145
- TP1：164
- TP2：168.5
- TP1 Protection：157.5
- TP2 Protection：164

### Position

- Recommended Current Position：0%
- Planned Initial Position：5%
- Maximum Position：15%
- Risk Budget：0.75%

### Institutional

- Stock Institutional Score：68/100
- Individual Flow Score：67/100
- Data Quality：FULL
- 外資 5D：71783 張
- 三大法人 5D：141751 張
- 外資 20D：58146 張
- 三大法人 20D：188847 張

## Validation

- Status：OK
- All required snapshot fields parsed successfully.

## Snapshot Policy

- Snapshot 只整合既有模型輸出，不重新計算 Direction 或 Confidence；Execution 可顯示 Corporate Action Layer 的 override。
- Snapshot 用於盤前 / 盤後決策介面，不取代原始完整報告。
- 模型公式、詳細權重與內部計算邏輯不輸出至精簡 Snapshot。
- Private repository 仍為完整模型的唯一主要來源。
