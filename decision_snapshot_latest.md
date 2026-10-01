# Decision Snapshot V1

更新時間：2026-10-02T07:03:30.094859+08:00
Session：PREMARKET
Report Date：2026-10-02
Latest Market Trade Date：2026-10-01
Freshness：PASS

## TAIEX

- Direction：72/100
- Confidence：67/100
- Regime：Risk-on Bias
- Action：偏多但控制部位
- Event Risk：0/100

### Market Structure

- Market Health：FRAGILE (49.8)
- Breadth：43.4/100；NARROW RALLY / WARNING
- Participation：MIXED (52.8)
- Concentration：N/A
- Rotation / Risk Appetite：MIXED / 74.6
- Breadth Divergence：N/A (INSUFFICIENT_HISTORY)

### Active ETF Data

- Data Quality：PARTIAL
- Holdings / Shares / Units Coverage：3.45% / 100.0% / 0.0%
- Diagnostic only；本階段不產生交易訊號。

## 台積電（2330）

- Price：2510
- Direction：78/100
- Confidence：77/100
- Decision：偏多
- Execution：WAIT FOR BETTER PRICE
- Chase Risk：60/100
- R/R Gate：BLOCK

### Entry

- Entry Zone 1：2480 ～ 2495
- Entry Zone 2：2455 ～ 2470
- Breakout：2515

### Exit

- Hard Stop：2435
- TP1：2510
- TP2：2530
- TP1 Protection：2500
- TP2 Protection：2510

### Position

- Recommended Current Position：0%
- Planned Initial Position：10%
- Maximum Position：20%
- Risk Budget：1%

### Institutional

- Stock Institutional Score：72/100
- Individual Flow Score：70/100
- Data Quality：FULL
- 外資 5D：2512 張
- 三大法人 5D：3756 張
- 外資 20D：-14641 張
- 三大法人 20D：-8550 張

## 聯電（2303）

- Price：161.5
- Direction：72/100
- Confidence：67/100
- Decision：偏多
- Execution：INVALID SETUP / NO TRADE
- Chase Risk：86/100
- R/R Gate：POOR

### Entry

- Entry Zone 1：155 ～ 158
- Entry Zone 2：144 ～ 146.5
- Breakout：169

### Exit

- Hard Stop：148
- TP1：168.5
- TP2：176.5
- TP1 Protection：161.5
- TP2 Protection：169.5

### Position

- Recommended Current Position：0%
- Planned Initial Position：5%
- Maximum Position：15%
- Risk Budget：0.75%

### Institutional

- Stock Institutional Score：57/100
- Individual Flow Score：48/100
- Data Quality：FULL
- 外資 5D：-33421 張
- 三大法人 5D：-24291 張
- 外資 20D：24490 張
- 三大法人 20D：154855 張

## Validation

- Status：OK
- All required snapshot fields parsed successfully.

## Snapshot Policy

- Snapshot 只整合既有模型輸出，不重新計算 Direction 或 Confidence；Execution 可顯示 Corporate Action Layer 的 override。
- Snapshot 用於盤前 / 盤後決策介面，不取代原始完整報告。
- 模型公式、詳細權重與內部計算邏輯不輸出至精簡 Snapshot。
- Private repository 仍為完整模型的唯一主要來源。
