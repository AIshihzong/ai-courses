# 07｜電腦視覺、擴散模型、多模態與語音

> 適合對象：對影像辨識、影像／影片生成、多模態模型或語音 AI 有興趣的學習者。
> 趨勢：傳統電腦視覺課程（CNN、物件偵測）與生成式影像課程（擴散模型、流匹配 Flow Matching）正在融合；多模態模型（同時處理文字、影像、聲音）成為新主角。

[← 回到總覽](../README.md)

## 速覽

| # | 課程（中文譯名／英文原名） | 提供者 | 程度 | 費用 | 重點 |
|---|---|---|---|---|---|
| 1 | 史丹佛 CS231n 電腦視覺深度學習 / CS231n: Deep Learning for Computer Vision | 史丹佛大學 | ⭐⭐～⭐⭐⭐ | 筆記與錄影免費 | 電腦視覺經典 |
| 2 | 密西根大學電腦視覺深度學習 / EECS 498/598: Deep Learning for Computer Vision | 密西根大學 | ⭐⭐～⭐⭐⭐ | 免費 | CS231n 延伸版 |
| 3 | Hugging Face 電腦視覺社群課程 / Community Computer Vision Course | Hugging Face 社群 | ⭐⭐ | 免費 | 現代 CV 實作 |
| 4 | Hugging Face 擴散模型課程 / Diffusion Course | Hugging Face | ⭐⭐ | 免費 | diffusers 實作 |
| 5 | MIT 流匹配與擴散模型 / MIT 6.S184: Generative AI with SDEs | MIT | ⭐⭐⭐ | 免費 | 擴散與流匹配理論 |
| 6 | 史丹佛 CME296 擴散與大型視覺模型 / CME296: Diffusion & Large Vision Models | 史丹佛大學 | ⭐⭐⭐ | 教材免費 | 擴散 Transformer |
| 7 | 擴散模型如何運作 / How Diffusion Models Work | DeepLearning.AI | ⭐⭐ | 免費觀看 | 1 小時入門短課 |
| 8 | 視覺與多模態理解的現代 AI 模型 / Modern AI Models for Vision and Multimodal Understanding | 科羅拉多大學波德分校（Coursera） | ⭐⭐ | 付費（有試用期） | CLIP、多模態 |
| 9 | Hugging Face 語音課程 / Audio Course | Hugging Face | ⭐⭐ | 免費 | 語音辨識與合成 |

---

## 1. 史丹佛 CS231n：電腦視覺深度學習（CS231n: Deep Learning for Computer Vision）

- **提供者**：史丹佛大學，李飛飛（Fei-Fei Li）團隊
- **程度**：⭐⭐ 中級～⭐⭐⭐ 進階｜**費用**：課程筆記公開免費；YouTube 有官方釋出的歷年錄影
- **連結**：<https://cs231n.stanford.edu/>｜課程筆記 <https://cs231n.github.io/>

**簡介**：深度學習時代最具影響力的課程之一，啟蒙了無數研究者與工程師。作業先以 NumPy 從零實作，再進入 PyTorch。

**你會學到**：影像分類、損失函數與最佳化、反向傳播、CNN 架構、訓練技巧、物件偵測與分割、視覺化與可解釋性、生成式模型（含擴散模型）、自監督學習、視覺 Transformer、3D 視覺等。

**點評**：電腦視覺必修經典。課程筆記本身就是極佳的深度學習教材，即使不專攻視覺也值得閱讀前幾章。

---

## 2. 密西根大學電腦視覺深度學習（EECS 498-007/598-005: Deep Learning for Computer Vision）

- **提供者**：密西根大學，Justin Johnson（CS231n 前講師）
- **程度**：⭐⭐～⭐⭐⭐｜**費用**：錄影、投影片與作業免費
- **連結**：<https://web.eecs.umich.edu/~justincj/teaching/eecs498/>

**點評**：內容可視為 CS231n 的擴充版，錄影完整、作業品質高，非常適合自學者完整跟完一學期。

---

## 3. Hugging Face 電腦視覺社群課程（Community Computer Vision Course）

- **提供者**：Hugging Face 社群
- **程度**：⭐⭐ 中級｜**費用**：免費
- **連結**：<https://huggingface.co/learn/computer-vision-course>

**簡介**：由社群協作撰寫，從 CNN 基礎到視覺 Transformer、多模態模型、生成式模型、影片與 3D 視覺，搭配 Hugging Face 函式庫實作。

**點評**：內容新、實作導向，適合想快速使用現代預訓練視覺模型的工程師。部分第三方整理指出本課程不提供證書。

---

## 4. Hugging Face 擴散模型課程（Diffusion Course）

- **提供者**：Hugging Face
- **程度**：⭐⭐ 中級｜**費用**：免費｜**時長**：4 個單元
- **連結**：<https://huggingface.co/learn/diffusion-course>

**簡介**：介紹擴散模型的理論與 `diffusers` 函式庫的使用，從從零訓練小型擴散模型、微調與引導（Guidance），到 Stable Diffusion 與創意應用。

**點評**：學習影像生成實作的最佳免費入門之一。

---

## 5. MIT 流匹配與擴散模型（MIT 6.S184: Generative AI with Stochastic Differential Equations）

- **提供者**：MIT（Peter Holderrieth、Ezra Erives）
- **程度**：⭐⭐⭐ 進階｜**費用**：講義、錄影與實作免費
- **連結**：<https://diffusion.csail.mit.edu/>

**簡介**：以隨機微分方程的觀點，嚴謹推導**流匹配（Flow Matching）與擴散模型**，並實作影像生成模型。

**點評**：數學要求較高，但講義寫得相當清楚，是理解現代影像／影片／分子生成模型的優秀理論課。

---

## 6. 史丹佛 CME296：擴散與大型視覺模型（Diffusion & Large Vision Models）

- **提供者**：史丹佛大學
- **程度**：⭐⭐⭐ 進階｜**費用**：據 2026 年 6 月報導，完整講座教材已免費公開
- **資料來源**：<https://www.i-programmer.info/news/150-training-a-education/18939-stanfords-cme296-diffusion-a-large-vision-models.html>

**主題**：擴散模型基礎、分數匹配（Score Matching）與流匹配、擴散 Transformer（DiT）、可控影像生成與評估。

**點評**：適合已懂基礎、想跟上大型視覺生成模型最新架構的人。（本條資訊來自二手報導，請以史丹佛官方頁面為準。）

---

## 7. 擴散模型如何運作（How Diffusion Models Work）

- **提供者**：DeepLearning.AI，Sharon Zhou 主講
- **程度**：⭐⭐｜**費用**：影片可免費觀看｜**時長**：約 1 小時
- **連結**：<https://www.deeplearning.ai/short-courses/how-diffusion-models-work/>

**點評**：以程式碼一步步建立擴散模型的直覺，適合作為第 4–6 項之前的熱身。

---

## 8. 視覺與多模態理解的現代 AI 模型（Modern AI Models for Vision and Multimodal Understanding）

- **提供者**：科羅拉多大學波德分校（Coursera）
- **程度**：⭐⭐｜**費用**：Coursera 付費（7 天免費試用）｜**時長**：約 3 小時
- **連結**：<https://www.coursera.org/learn/modern-ai-models-vision-multimodal-understanding>

**簡介**：涵蓋 CLIP 等對比學習模型與擴散影像生成，屬於該校線上碩士學位的課程之一。

**點評**：適合想取得學分或正式證書的學習者；只求知識可優先選擇免費資源。

---

## 9. Hugging Face 語音課程（Audio Course）

- **提供者**：Hugging Face
- **程度**：⭐⭐ 中級｜**費用**：免費（可取得證書）
- **連結**：<https://huggingface.co/learn/audio-course>

**簡介**：將 Transformer 應用於音訊資料：音訊分類、自動語音辨識（ASR，如 Whisper）、語音合成（TTS）與建立語音助理。

**點評**：語音 AI 的免費入門首選。若想打造即時語音代理，可接續 DeepLearning.AI 的語音代理短課（見 [06｜AI 代理](06-ai-agents.md)）。

---

## 本類別選課建議

| 你的目標 | 建議路線 |
|---|---|
| 電腦視覺工程師 | CS231n（筆記 + 作業）→ Hugging Face CV Course |
| 影像生成入門 | DeepLearning.AI 擴散短課 → Hugging Face Diffusion Course |
| 影像生成研究 | MIT 6.S184 → 史丹佛 CME296 |
| 多模態應用 | Hugging Face CV Course（多模態章節）→ 各模型廠商的多模態 API 文件 |
| 語音 AI | Hugging Face Audio Course |
