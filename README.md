# -顯卡CP值GPU CP-
作用於對cp值的主要提示，專用於新台幣，轉換幣值時請轉新台幣(This is the main prompt for CP value, specifically for New Taiwan Dollars (NTD). Please convert to New Taiwan Dollars when changing currency.)如有看不懂的地方請使用翻譯(Please use a translator if you encounter any parts you don't understand.)

中文說明：
# 顯卡對比 (GPU Compare) v7.4

### ⚠️ 重要聲明：純原生硬體物理限制檢測 ⚠️
本工具評定的是 **「純原生硬體物理限制」**。這是一個冷酷的硬體底標，完全 **「沒有任何軟體介入」**（不考慮 DLSS、補幀或驅動優化）。它計算的是顯卡在物理層面上「能扛住多少數據」。軟體可以美化幀數，但無法改變位寬狹窄或顯存溢出導致的物理崩潰。

---

## 一、 實力分子：CP 值的真本質
**公式：`[顯存容量] x [位寬 Bit] x [速度係數] x [穩定度加成]`**

* **速度係數**：衡量數據傳輸帶的物理等級 (GDDR7 > GDDR6X > GDDR6)。
* **穩定度加成**：衡量位寬對高壓環境的「物理耐壓度」(512-bit > 352-bit)。

> **核心概念**：分子代表實體規格。如果規格被砍，不論軟體如何吹捧，CP 值都會直接現形。

---

## 二、 分母公式：環境與價格雙重壓力
**公式：`[價格(萬)] x [總解析度壓力] x [同步壓力]`**

1.  **價格壓力 (萬)**：價格越高，分母就越重。昂貴的顯卡必須拿出更強大的「分子規格」對抗，否則分數會極難看。
2.  **解析度壓力 (Load)**：4K = 4.0 | 2K = 1.77 | 1080p = 1.0。
3.  **同步壓力 (Sync)**：多螢幕環境下，系統處理不同步訊號產生的物理額外開銷。

---

## 三、 生存紅線：2K / 4K 階梯獎懲
這是不講情面的「硬體門檻」，不達標就直接重罰：

#### 🔴 4K 環境 (門檻：16GB)
* **獎勵**：20GB 以上 (1.48x)、24GB 以上 (1.62x)、32GB 以上 (1.75x)。
* **懲罰**：低於 16GB 直接 **重罰 0.5x**。顯存不足，硬體地基直接崩塌。

#### 🟡 2K 環境 (門檻：12GB)
* **懲罰**：低於 12GB **重罰 0.5x**。
* **警告**：12GB ~ 14GB 性能打 7 折 (0.7x)。
* **理由**：12GB 是維持 2K 原生高畫質穩定的「物理底線」。

---

## 四、 分數等級解釋
* **> 10.00 優質配置**：CP 值極高。跑不動通常是核心架構上限，而非硬體規格偷料。
* **5.00 ~ 10.00 安全配置**：規格在及格線上，沒有太多物理餘裕。
* **< 5.00 不合格**：硬體先天殘疾，根本不該在該解析度下運作。

---

## 五、 關於「魔改卡」與空間換取時間
魔改卡（如 **2080 Ti 22G**）體現了最硬核的道理：
1.  **為什麼能全開？**：雖然核心算力舊，但 22GB 顯存與 352-bit 位寬承擔了物理上的「爆顯存」風險。
2.  **原生邏輯**：當核心算得慢，數據必須有足夠的「物理空間」緩衝。
3.  **結論**：高分證明了「純硬體料件」如何擊敗老黃的「刀法」。

英文說明:
# GPU-Compare (Hardware Baseline Calculator) v7.4

### ⚠️ IMPORTANT: Pure Native Hardware Limitation Analysis ⚠️
This tool evaluates the **"Pure Native Hardware Baseline."** This is a cold, hard measurement of hardware limits, with **ZERO software intervention** (NO DLSS, NO Frame Gen, NO Driver-level hacks). It calculates how much data a GPU can physically handle at its core. Software can beautify your framerate, but it cannot fix a physical collapse caused by narrow bus widths or VRAM overflow.

---

## 1. The Numerator: The Essence of Hardware Value
**Formula: `[VRAM Capacity] x [Bus Width] x [Speed Factor] x [Stability Multiplier]`**

* **Speed Factor**: Measures the physical grade of the data highway (GDDR7 > GDDR6X > GDDR6).
* **Stability Multiplier**: Measures the "Physical Pressure Resistance" of the bus width (512-bit > 352-bit > 256-bit).

> **Core Concept**: The numerator represents the physical "materials" you actually paid for. If the specs are cut, the hardware CP value will drop immediately, no matter how much the marketing hype tries to hide it.

---

## 2. The Denominator: Price & Environment Pressure
**Formula: `[Price (in 10k units)] x [Total Resolution Load] x [Sync Factor]`**

1.  **Price Pressure**: The more expensive the card, the heavier the denominator. A premium card MUST provide superior "Numerator Specs" to justify its cost, or the score will be abysmal.
2.  **Resolution Load**: 4K = 4.0 | 2K = 1.77 | 1080p = 1.0.
    * *Calculation: Primary Display Weight + (Secondary Display Weight x 0.3)*
3.  **Sync Factor**: The physical overhead caused by handling mismatched signals (different resolutions/refresh rates) in multi-monitor setups.

---

## 3. Survival Redlines: 2K / 4K Hardware Thresholds
These are uncompromising "Hardware Gates." Failure to meet them results in a severe penalty:

#### 🔴 4K Environment (Threshold: 16GB)
* **Bonus**: 20GB+ (1.48x), 24GB+ (1.62x), 32GB+ (1.75x).
* **Penalty**: Below 16GB results in a **0.5x Heavy Penalty**. Without enough VRAM, the hardware foundation collapses under 4K pressure.

#### 🟡 2K Environment (Threshold: 12GB)
* **Penalty**: Below 12GB results in a **0.5x Heavy Penalty**.
* **Warning**: 12GB ~ 14GB results in a **0.7x Performance Cut**.
* **Logic**: 12GB is the absolute "Physical Bottom Line" for maintaining stability at native 2K ultra settings.

---

## 4. Score Evaluation
* **> 10.00 Premium Build**: High hardware CP value. Any performance issues are likely due to GPU architecture limits, not hardware corner-cutting.
* **5.00 - 10.00 Safe Build**: Specs are right on the line. No physical surplus; performance depends heavily on the GPU core.
* **< 5.00 Failed**: Physical handicap. The card was never meant to operate at this resolution.

---

## 5. Modded Cards & "Space for Time"
Modded GPUs (e.g., **RTX 2080 Ti 22GB**) embody a brutal hardware truth:
1.  **Why can it handle Max Settings?**: Although the core is older, the 22GB VRAM and 352-bit bus physically eliminate the risk of "VRAM Overflow."
2.  **Native Logic**: When the core isn't fast enough, the data must have enough "Physical Buffer" (VRAM) to wait.
3.  **Conclusion**: A high score proves how "Pure Hardware Specs" can defeat corporate "Product Segmentation" (the "Gimped" specs from manufacturers).
