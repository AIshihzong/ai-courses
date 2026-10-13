# 03｜深度學習

> 適合對象：已有 Python 與基礎機器學習概念，想理解並實作神經網路的人。
> 深度學習是現代 AI（含 LLM、影像生成）的核心。本類別課程分為「由上而下」（先會用再懂原理）與「由下而上」（從數學與零開始實作）兩種風格，可依個性挑選。

[← 回到總覽](../README.md)

## 速覽

| # | 課程（中文譯名／英文原名） | 提供者 | 程度 | 費用 | 風格 |
|---|---|---|---|---|---|
| 1 | 深度學習專項課程 / Deep Learning Specialization | DeepLearning.AI（吳恩達） | ⭐⭐ | 部分免費 | 由下而上、系統化 |
| 2 | 程式設計師的實用深度學習 / Practical Deep Learning for Coders | fast.ai | ⭐⭐ | 免費 | 由上而下、實作優先 |
| 3 | MIT 深度學習導論 / MIT 6.S191 Introduction to Deep Learning | MIT | ⭐⭐ | 免費 | 密集短期、涵蓋前沿 |
| 4 | 神經網路：從零到英雄 / Neural Networks: Zero to Hero | Andrej Karpathy | ⭐⭐～⭐⭐⭐ | 免費 | 從零手刻 |
| 5 | 動手學深度學習 / Dive into Deep Learning (D2L) | 李沐等 | ⭐⭐ | 免費 | 互動式教科書 |
| 6 | 紐約大學深度學習 / NYU Deep Learning | Yann LeCun、Alfredo Canziani | ⭐⭐⭐ | 免費 | 研究導向 |
| 7 | 給初學者的 AI / AI for Beginners | 微軟 | ⭐ | 免費（GitHub） | 課綱式教材 |
| 8 | 理解深度學習 / Understanding Deep Learning | Simon J.D. Prince | ⭐⭐～⭐⭐⭐ | 免費電子書 | 教科書 + 習題 |
| 9 | 史丹佛 CS230 深度學習 / CS230: Deep Learning | 史丹佛大學 | ⭐⭐ | 錄影免費 | 專案導向 |

---

## 1. 深度學習專項課程（Deep Learning Specialization）

- **提供者**：DeepLearning.AI，吳恩達主講
- **程度**：⭐⭐ 中級｜**費用**：Coursera 首個模組可免費預覽，完整內容與證書需付費（可申請助學金）｜**時長**：5 門課，約 3–5 個月
- **連結**：Coursera <https://www.coursera.org/specializations/deep-learning>｜DeepLearning.AI 官網 <https://www.deeplearning.ai/specializations/deep-learning>（評分作業與證書需 DeepLearning.AI Pro 會員，官網標示年繳約每月 25 美元）

**課程組成**：
1. 神經網路與深度學習（Neural Networks and Deep Learning）
2. 改善深度神經網路：超參數調整、正則化與最佳化（Improving Deep Neural Networks）
3. 機器學習專案的結構化（Structuring Machine Learning Projects）
4. 卷積神經網路（Convolutional Neural Networks）
5. 序列模型（Sequence Models）：RNN、LSTM、注意力機制與 Transformer 入門

**點評**：被譽為深度學習「標準教材」，從反向傳播的數學一步步推導，觀念非常扎實。第 3 門「專案結構化」講述的除錯與誤差分析方法至今仍極具價值。缺點是框架（TensorFlow/Keras）與內容較舊，LLM 部分只到 Transformer 入門，需另行補充。

---

## 2. 程式設計師的實用深度學習（Practical Deep Learning for Coders）

- **提供者**：fast.ai（Jeremy Howard、Rachel Thomas）
- **程度**：⭐⭐ 中級｜**費用**：免費｜**時長**：第一部分 9 堂、每堂約 90 分鐘
- **連結**：<https://course.fast.ai/>

**簡介**：「由上而下」教學法的代表：第一堂課就讓你訓練出可用的影像分類模型並部署，之後才逐步揭開背後原理。使用 PyTorch 與 fastai 函式庫。

**課程組成**：
- 第一部分：影像分類、部署、表格資料、自然語言處理、協同過濾、從零打造神經網路等
- 第二部分：從深度學習基礎到 Stable Diffusion（From Deep Learning Foundations to Stable Diffusion）

**點評**：對「先看到成果才有動力」的工程師非常友善，也有大量社群資源。需留意目前最新版本為 2022 年版，部分工具與 LLM 內容需自行補充。fast.ai 團隊另與 Answer.AI 推出付費課程 *How to Solve It With Code*，與本課程是不同的課。

---

## 3. MIT 深度學習導論（MIT 6.S191: Introduction to Deep Learning）

- **提供者**：MIT（Alexander Amini、Ava Amini）
- **程度**：⭐⭐ 中級｜**費用**：免費（投影片、錄影與實作程式全部公開）｜**時長**：每年 1 月的密集課程，約 9 堂講座 + 3 個實作
- **連結**：<https://introtodeeplearning.com/>

**簡介**：MIT 每年更新的深度學習密集課程，2026 年版於 1 月 5–9 日開課。內容從基礎一路講到前沿主題。

**2026 年版主題**：深度序列模型、電腦視覺、生成式模型、強化學習、新前沿、AI 於科學的應用、大規模平行訓練等；實作包含**以深度學習生成音樂、人臉偵測系統、微調大型語言模型**。實作程式以 MIT 授權公開於 GitHub。

**先備條件**：基本矩陣運算、導數與連鎖律；熟悉 Python 有幫助但非必要。

**點評**：每年更新，是快速掌握「深度學習全景 + 最新進展」的好選擇。課程密集，建議搭配其他課程深入特定主題。外部學習者沒有證書。

---

## 4. 神經網路：從零到英雄（Neural Networks: Zero to Hero）

- **提供者**：Andrej Karpathy（前 OpenAI 創始成員、前 Tesla AI 總監）
- **程度**：⭐⭐ 中級～⭐⭐⭐ 進階｜**費用**：免費（YouTube + GitHub）｜**時長**：約 9 支長影片，每支 1–4 小時
- **連結**：<https://karpathy.ai/zero-to-hero.html>

**簡介**：從一個只有數十行的自動微分引擎（micrograd）開始，一步步手刻語言模型，最後**從零重現 GPT-2**。全程寫程式，不靠任何黑盒子。

**課程內容**：
- micrograd：從零實作反向傳播
- makemore 系列：字元級語言模型、多層感知器、BatchNorm、手動反向傳播、WaveNet
- 從零打造 GPT（Let's build GPT）
- GPT 分詞器（Tokenizer）
- 重現 GPT-2（124M）

**點評**：被許多人評為「理解神經網路與 LLM 最好的課程」。Karpathy 後續於 2025 年推出開源專案 **nanochat**，用約 8,000 行程式碼示範完整的類 ChatGPT 訓練流程，作為其籌備中的 LLM101n 課程結業專案（見 [04｜NLP 與 LLM](04-nlp-llm.md)）。

---

## 5. 動手學深度學習（Dive into Deep Learning, D2L）

- **提供者**：李沐、Aston Zhang、Zachary C. Lipton、Alexander J. Smola
- **程度**：⭐⭐ 中級｜**費用**：免費線上閱讀｜**語言**：英文版與**中文版**
- **連結**：英文 <https://d2l.ai/>｜中文 <https://zh.d2l.ai/>

**簡介**：每一節都是可執行的 Jupyter Notebook 的互動式教科書，同時提供 PyTorch、TensorFlow、JAX 等多種框架實作，被全球數百所大學採用為教材。李沐另在 B 站以中文錄製完整配套課程。

**點評**：理論、數學與程式碼三者結合得最好的教科書之一，中文讀者尤其推薦。詳見 [11｜中文原生課程](11-chinese-resources.md)。

---

## 6. 紐約大學深度學習（NYU Deep Learning）

- **提供者**：紐約大學，Yann LeCun（圖靈獎得主）、Alfredo Canziani
- **程度**：⭐⭐⭐ 進階｜**費用**：免費（錄影、投影片、筆記）
- **連結**：<https://atcold.github.io/NYU-DLSP21/>

**簡介**：研究導向的深度學習課程，特色是深入講解**能量基礎模型（Energy-Based Models）**、自監督學習、聯合嵌入架構等 LeCun 團隊的研究視角。前一年度（2020）的課程網站有社群協作的多國語言翻譯（含中文）。

**點評**：適合已掌握基礎、想理解研究前沿思路的學習者。

---

## 7. 給初學者的 AI（AI for Beginners）

- **提供者**：微軟
- **程度**：⭐ 入門｜**費用**：免費開源｜**時長**：12 週、24 課
- **連結**：<https://github.com/microsoft/AI-For-Beginners>

**簡介**：以 Jupyter Notebook 為主的課綱式教材，涵蓋符號式 AI、神經網路、電腦視覺、自然語言處理、生成對抗網路、強化學習入門與 AI 倫理，同時提供 PyTorch 與 TensorFlow 範例。

**點評**：需要基本 Python 能力，並非零程式課程。廣度足、深度普通，適合作為教師授課素材或自學者的「地圖」。

---

## 8. 理解深度學習（Understanding Deep Learning）

- **提供者**：Simon J.D. Prince（MIT Press，2023）
- **程度**：⭐⭐～⭐⭐⭐｜**費用**：電子書與配套 Notebook 免費
- **連結**：<https://udlbook.github.io/udlbook/>

**簡介**：近年評價極高的深度學習教科書，圖解清晰，涵蓋 Transformer、擴散模型、圖神經網路、強化學習等現代主題，並附有大量 Python Notebook 練習。

**點評**：適合作為任何深度學習課程的「主教材」或參考書。

---

## 9. 史丹佛 CS230 深度學習（CS230: Deep Learning）

- **提供者**：史丹佛大學，吳恩達、Kian Katanforoosh
- **程度**：⭐⭐ 中級｜**費用**：課程網站與歷年錄影免費
- **連結**：<https://cs230.stanford.edu/>

**簡介**：與 Coursera 深度學習專項課程搭配的校內課程，課堂著重專案實務、職涯建議與案例討論。

**點評**：已修過 Coursera 專項課程的人，可透過 CS230 錄影補充「如何做好一個深度學習專案」的經驗。

---

## 本類別選課建議

| 你的個性／目標 | 建議 |
|---|---|
| 喜歡先看到成果 | fast.ai → Karpathy Zero to Hero |
| 喜歡按部就班、打好理論 | 吳恩達 Deep Learning Specialization → Understanding Deep Learning |
| 想深刻理解 LLM 原理 | Karpathy Zero to Hero（必看）→ [04｜NLP 與 LLM](04-nlp-llm.md) |
| 時間有限、想掌握全景 | MIT 6.S191（一週看完） |
| 偏好中文 | 李沐《動手學深度學習》+ B 站課程、李宏毅「機器學習」 |
| 想走研究 | Understanding Deep Learning + NYU Deep Learning + 史丹佛專題課程 |
