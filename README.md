# -Graphics-Card-Comparison-
作用於對cp值的主要提示，專用於新台幣，轉換幣值時請轉新台幣(This is the main prompt for CP value, specifically for New Taiwan Dollars (NTD). Please convert to New Taiwan Dollars when changing currency.)

中文說明：
===========================================================
版本：v7.4
授權：GNU General Public License v3.0 (GPL-3.0)
核心理念：數據地基決定生存上限，軟體補償不計入硬體資產。

【⚠️ 重要聲明：純原生硬體黨的最後防線 ⚠️】
[span_0](start_span)本計算機評定的是「純原生硬體物理限制」[span_0](end_span)[span_1](start_span)。這是一個冷酷的硬體底標，完全「不計入任何軟體介入」，不考慮 DLSS、不考慮補幀、不考慮任何驅動優化[span_1](end_span)。

[span_2](start_span)我們只關心：當所有 AI 幻術消失時，這張顯卡在物理層面上「能扛住多少數據」[span_2](end_span)。這並非針對所有使用者，而是專為追求零延遲、真實像素、以及對抗廠商閹割規格的「純原生玩家」打造的檢測工具。

-----------------------------------------------------------
一、 實力分子：CP 值的真本質 (硬體買到多少料)
-----------------------------------------------------------
[span_3](start_span)公式：[顯存容量] x [位寬 Bit] x [速度係數] x [穩定度加成][span_3](end_span)

1. [span_4](start_span)速度係數：衡量數據傳輸帶的物理等級 (GDDR7 > GDDR6X > GDDR6)[span_4](end_span)。
2. [span_5](start_span)穩定度加成：衡量位寬對高壓環境的「物理耐壓度」 (512-bit > 352-bit)[span_5](end_span)。

技術細節：
- [span_6](start_span)分子代表你付出的金錢換回了多少實體規格[span_6](end_span)。
- 當位寬或頻寬不足，核心算力再強也會因為「等不到數據」而空轉（數據飢餓）。
- 軟體技術會隨世代更迭而過時，但物理頻寬資產永遠存在。

-----------------------------------------------------------
二、 分母公式：環境與價格雙重壓力
-----------------------------------------------------------
[span_7](start_span)公式：[價格(萬)] x [總解析度壓力] x [同步壓力][span_7](end_span)

1. 價格壓力 (萬元基準)：
   - [span_8](start_span)老黃的定價邏輯通常已包含算力紅利，故價格越高，分母越重[span_8](end_span)。
   - [span_9](start_span)昂貴的卡必須拿出對等的物理規格來對抗分母，否則分數會極難看[span_9](end_span)。
2. 解析度負載 (Load)：
   - 4K = 4.0 | 2K = 1.77 | [span_10](start_span)1080p = 1.0[span_10](end_span)。
   - [span_11](start_span)計算：主螢幕權重 + (副螢幕權重 x 0.3)[span_11](end_span)。
3. [span_12](start_span)同步壓力 (Sync)：多螢幕環境下處理不同步訊號的物理額外開銷[span_12](end_span)。

-----------------------------------------------------------
三、 生存紅線：2K / 4K 環境的階梯獎懲
-----------------------------------------------------------
在物理數據面前，顯存不足就是廢紙，本工具將直接重罰：

【4K 環境 (門檻：16GB)】
- [span_13](start_span)獎勵：20GB+(1.48x)、24GB+(1.62x)、32GB+(1.75x)[span_13](end_span)。
- [span_14](start_span)懲罰：低於 16GB 直接重罰 0.5x。物理緩衝區不足將導致 4K 環境崩潰[span_14](end_span)。

【2K 環境 (門檻：12GB)】
- [span_15](start_span)懲罰：低於 12GB 重罰 0.5x[span_15](end_span)。
- [span_16](start_span)警告：12GB ~ 14GB 處於黃線區，性能打 7 折 (0.7x)[span_16](end_span)。

-----------------------------------------------------------
四、 分數等級解釋
-----------------------------------------------------------
【 > 10.00 優質配置 】
- [span_17](start_span)對標「效能全開」無壓力。代表硬體地基穩固，能維持極高的 1% Low FPS[span_17](end_span)。

【 5.00 ~ 10.00 安全配置 】
- [span_18](start_span)對標「效能全開」尚可。規格在及格線上，建議視核心算力適度調整畫質[span_18](end_span)。

【 < 5.00 不合格 】
- [span_19](start_span)對標「效能全開」極易崩潰。硬體先天殘疾，不建議在該解析度下運作[span_19](end_span)。

-----------------------------------------------------------
五、 關於「魔改卡」與「原生邏輯」
-----------------------------------------------------------
如 2080 Ti 22G 等魔改卡在高解析度下表現優異，證明了：
1. [span_20](start_span)物理空間：當核心運算較慢時，巨量顯存提供了緩衝餘裕[span_20](end_span)。
2. [span_21](start_span)抗壓性：充足的頻寬與容量能擊敗現代被閹割位寬的「刀法」卡[span_21](end_span)。

-----------------------------------------------------------
六、 開源與版權聲明
-----------------------------------------------------------
本工具採 GNU GPL v3 授權。
1. 您可以自由分發、修改此代碼。
2. 若您修改並發布此代碼，必須同樣以 GPL v3 授權開源。
3. 價格基準建議以「台幣萬元」為準，其他幣值請自行轉換。
===========================================================

English instruction manual:
===========================================================
Version: v7.4
License: GNU General Public License v3.0 (GPL-3.0)
Core Concept: Physical foundation determines performance ceiling.

[⚠️ WARNING: FOR NATIVE HARDWARE ENTHUSIASTS ONLY ⚠️]
This calculator evaluates "Pure Native Hardware Physical Limits." It is a cold, 
objective baseline that ignores all software interventions, including DLSS, 
[span_22](start_span)Frame Generation, and AI Upscaling[span_22](end_span).

We focus solely on: "How much data can this GPU physically handle?" This is 
designed for "Native Gamers" who demand zero latency, true pixels, and resistance 
[span_23](start_span)against "gimped" hardware specs[span_23](end_span).

-----------------------------------------------------------
1. The Numerator: Hardware Asset Value (Molecular)
-----------------------------------------------------------
[span_24](start_span)Formula: [VRAM] x [Bit Width] x [Speed Factor] x [Stability Multiplier][span_24](end_span)

- Speed Factor: GDDR7 (1.55) | GDDR6X (1.28) | [span_25](start_span)GDDR6 (1.00)[span_25](end_span).
- Stability: 512-bit (1.48) | 384-bit (1.35) | 256-bit+ (1.22) | [span_26](start_span)128-bit (0.82)[span_26](end_span).

Key Logic: This represents the physical "raw material" you purchased. 
If memory bandwidth is insufficient, even the strongest GPU core will stall 
(Data Starvation). Software may fade, but physical bandwidth remains constant.

-----------------------------------------------------------
2. The Denominator: Environmental & Price Pressure
-----------------------------------------------------------
[span_27](start_span)Formula: [Price (in 10k TWD)] x [Res Load] x [Sync Factor][span_27](end_span)

- Price Pressure: Expensive cards must provide superior physical specs to counter 
  [span_28](start_span)the denominator, otherwise the score will plummet[span_28](end_span).
- Resolution Load: 4K (4.0) | 2K (1.77) | [span_29](start_span)1080p (1.0)[span_29](end_span).
- [span_30](start_span)Sync Factor: Physical overhead of multi-monitor/asynchronous signals[span_30](end_span).

-----------------------------------------------------------
3. Survival Redline: VRAM Penalty System
-----------------------------------------------------------
In the face of raw data, insufficient VRAM is garbage. Heavy penalties apply:

[4K Environment (Threshold: 16GB)]
- [span_31](start_span)Rewards: 20GB+ (1.48x), 24GB+ (1.62x), 32GB+ (1.75x)[span_31](end_span).
- [span_32](start_span)Penalty: Below 16GB results in a 0.5x penalty (System collapse due to VRAM overflow)[span_32](end_span).

[2K Environment (Threshold: 12GB)]
- [span_33](start_span)Penalty: Below 12GB results in a 0.5x penalty[span_33](end_span).
- [span_34](start_span)Warning: 12GB ~ 14GB results in a 0.7x warning (Yellow Zone)[span_34](end_span).

-----------------------------------------------------------
4. Score Interpretations
-----------------------------------------------------------
- CP > 10.00 (Premium): Solid physical foundation. Capable of high "1% Low FPS" 
  [span_35](start_span)without micro-stuttering[span_35](end_span).
- 5.00 ~ 10.00 (Safe): Sufficient for the target resolution. Adjust settings 
  [span_36](start_span)based on core compute power[span_36](end_span).
- CP < 5.00 (Fail): Hardware is physically inadequate for this resolution. 
  [span_37](start_span)Likely to crash or stutter[span_37](end_span).

-----------------------------------------------------------
5. Open Source License
-----------------------------------------------------------
This tool is licensed under GNU GPL v3. 
- You are free to distribute and modify this code.
- Modified versions MUST also be open-sourced under GPL v3.
- Calibration is based on TWD ($10,000 unit). Adjust for currency differences.
===========================================================
