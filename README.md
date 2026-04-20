# taiwan-sarcopenia-prevention-guide

> 台灣肌少症預防指南：診斷標準、蛋白質需求與阻力運動處方

台灣 65 歲以上老年人肌少症盛行率約 **3.9–7.3%**（男性高於女性），社區老年人中高達 **14–33%** 有肌少症前期（NHRI，2020）。隨著台灣人口快速老化（2026 年預計超高齡社會），肌少症的預防與管理已成為公共衛生重大議題。

本資料庫收錄：

| 檔案 | 說明 | 筆數 |
|------|------|------|
| [`data/diagnostic-criteria.json`](data/diagnostic-criteria.json) | AWGS 2019 診斷標準（肌肉量、肌力、體能）| 12 項標準 |
| [`data/protein-requirements.json`](data/protein-requirements.json) | 高齡者蛋白質需求（ESPEN 2018 指引 × 台灣 DRI）| 9 項建議 |
| [`data/resistance-exercise-protocols.json`](data/resistance-exercise-protocols.json) | 阻力運動處方（頻率、強度、動作）| 8 項協議 |
| [`data/taiwan-prevalence-data.json`](data/taiwan-prevalence-data.json) | 台灣流行病學數據（NHRI 調查、橫斷研究）| 10 筆研究 |

## 肌少症診斷標準（AWGS 2019）

| 指標 | 男性切點 | 女性切點 | 測量方法 |
|------|---------|---------|---------|
| 四肢骨骼肌量指數（ASMI） | < 7.0 kg/m² | < 5.4 kg/m² | DXA |
| 四肢骨骼肌量指數（BIA） | < 7.0 kg/m² | < 5.7 kg/m² | BIA |
| 握力 | < 28 kg | < 18 kg | 握力計 |
| 步行速度 | < 1.0 m/s | < 1.0 m/s | 6 公尺步行測試 |
| 五次起坐時間 | > 12 秒 | > 12 秒 | 計時起坐測試 |

## 嚴重肌少症（Severe Sarcopenia）

肌肉量不足 **+** 肌力降低 **+** 體能表現不佳 = 嚴重肌少症

**亞洲肌少症工作小組（AWGS 2019）**：Chen LK et al. (2020) J Am Med Dir Assoc. **PMID: 31920071**

## 蛋白質建議（每公斤體重）

| 族群 | 建議量 | 來源 |
|------|--------|------|
| 健康老年人（≥ 65 歲） | 1.0–1.2 g/kg/day | ESPEN 2018 |
| 急性或慢性病老年人 | 1.2–1.5 g/kg/day | ESPEN 2018 |
| 嚴重疾病/術後老年人 | 1.5–2.0 g/kg/day | ESPEN 2018 |
| 台灣 DRI（70 歲以上） | 1.0 g/kg/day（最低限）| 衛福部 2023 |

每餐蛋白質達 **25–30g（含白胺酸 ≥ 2.5–3.0g）** 可最大化肌肉蛋白合成（MPS）。

## 台灣高白胺酸食物來源

| 食物 | 份量 | 蛋白質 | 白胺酸 |
|------|------|--------|--------|
| 雞胸肉 | 100g | 23g | ~1.8g |
| 豆腐（板豆腐） | 150g | 12g | ~0.9g |
| 鮭魚 | 100g | 22g | ~1.7g |
| 雞蛋 | 2 顆 | 12g | ~1.0g |
| 黃豆漿（無糖） | 400ml | 14g | ~1.0g |

**注意**：植物性蛋白白胺酸含量較低，純素老年人每餐需增加攝取量約 20–30%。

## 阻力運動核心建議

- **頻率**：每週 2–3 次，休息 ≥ 48 小時
- **強度**：1RM 的 60–80%（中至高強度）
- **組數**：每動作 2–4 組，每組 8–12 下
- **台灣適用動作**：坐姿伸腿、扶牆深蹲、彈力帶划船、啞鈴肩推

**Meta-analysis（Peterson MD 2011）**：單獨阻力訓練可增加老年人肌肉量 **+1.1 kg**，肌力提升 **+27%**。**PMID: 21537565**

## 資料來源

- **AWGS 2019**: Chen LK et al. (2020) PMID: 31920071
- **ESPEN Guidelines 2018**: Deutz NE et al. (2017) PMID: 28756328
- **Leucine threshold**: Paddon-Jones D & Rasmussen BB (2009) PMID: 19208091
- **Resistance training meta-analysis**: Peterson MD et al. (2011) PMID: 21537565
- **Taiwan prevalence**: Wu IC et al. (2014) PMID: 24646912
- **台灣 DRI 第八版（2023）**：衛福部國民健康署

## 免責聲明

本資料庫以公共衛生教育為目的。肌少症診斷與治療需由醫師或醫療團隊評估，本資料庫不構成醫療建議。

## License

MIT © taiwan-sarcopenia-prevention-guide contributors
