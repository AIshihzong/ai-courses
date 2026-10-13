# 02｜機器學習基礎與數學

> 適合對象：具備基本程式能力（建議會 Python），想真正理解機器學習原理的人。
> 這是通往深度學習、LLM 與 AI 工程的地基。即使你的目標是做 AI 應用，花 1–3 個月打好這層基礎，後面會走得更穩。

[← 回到總覽](../README.md)

## 速覽

| # | 課程（中文譯名／英文原名） | 提供者 | 程度 | 費用 | 估計時長 |
|---|---|---|---|---|---|
| 1 | 機器學習專項課程 / Machine Learning Specialization | DeepLearning.AI × 史丹佛（吳恩達） | ⭐～⭐⭐ | 部分免費 | 約 2–3 個月 |
| 2 | 史丹佛 CS229 機器學習 / CS229: Machine Learning | 史丹佛大學 | ⭐⭐⭐ | 教材與錄影免費 | 一學期 |
| 3 | Google 機器學習速成班 / Machine Learning Crash Course | Google | ⭐～⭐⭐ | 免費 | 約 15 小時 |
| 4 | Kaggle 微課程 / Kaggle Learn | Kaggle（Google） | ⭐～⭐⭐ | 免費（含證書） | 每門 3–5 小時 |
| 5 | 哈佛 CS50 人工智慧導論（Python）/ CS50's Introduction to AI with Python | 哈佛大學 | ⭐⭐ | 免費；edX 認證證書付費 | 約 7 週 |
| 6 | 給初學者的機器學習 / ML for Beginners | 微軟 | ⭐ | 免費（GitHub） | 12 週、26 課 |
| 7 | 機器學習與資料科學的數學 / Mathematics for ML and Data Science | DeepLearning.AI | ⭐～⭐⭐ | 部分免費 | 約 3 個月 |
| 8 | 機器學習的數學 / Mathematics for Machine Learning | 倫敦帝國學院 | ⭐⭐ | 部分免費 | 約 2–4 個月 |
| 9 | 線性代數的本質等系列 / Essence of Linear Algebra & more | 3Blue1Brown | ⭐ | 免費（YouTube） | 數小時 |
| 10 | MIT 18.06 線性代數 / Linear Algebra | MIT OpenCourseWare | ⭐⭐ | 免費 | 一學期 |
| 11 | StatQuest 統計與機器學習 / StatQuest | Josh Starmer | ⭐ | 免費（YouTube） | 自選 |

---

## 1. 機器學習專項課程（Machine Learning Specialization）

- **提供者**：DeepLearning.AI × 史丹佛線上（Stanford Online），吳恩達主講
- **程度**：⭐ 入門～⭐⭐ 中級｜**費用**：Coursera 首個模組可免費預覽，完整內容與證書需付費（可申請助學金）｜**時長**：3 門課，約 2–3 個月（每週約 10 小時）
- **連結**：<https://www.coursera.org/specializations/machine-learning-introduction>

**簡介**：2022 年改版的經典課程，前身是吳恩達 2012 年於 Coursera 開設、全球數百萬人修過的「Machine Learning」。新版改用 **Python**（舊版使用 Octave/MATLAB）。

**課程組成**：
1. 監督式學習：迴歸與分類（Supervised Machine Learning: Regression and Classification）
2. 進階學習演算法（Advanced Learning Algorithms）：神經網路、決策樹、模型評估
3. 非監督式學習、推薦系統與強化學習（Unsupervised Learning, Recommenders, Reinforcement Learning）

**點評**：全球公認最友善的機器學習入門課，直觀解釋與實作並重。缺點是內容屬於「LLM 之前」的經典機器學習，學完後應銜接深度學習與 LLM 課程。

---

## 2. 史丹佛 CS229 機器學習（CS229: Machine Learning）

- **提供者**：史丹佛大學
- **程度**：⭐⭐⭐ 進階｜**費用**：講義與歷年錄影免費（需付費才能取得學分或評分）｜**時長**：一學期
- **連結**：<https://cs229.stanford.edu/>

**簡介**：史丹佛的研究所等級機器學習課，著重**數學推導**：線性模型、廣義線性模型、生成式學習演算法、核方法、SVM、學習理論、EM 演算法、強化學習等。

**取得方式**：官網提供講義（lecture notes，非常經典）；YouTube「Stanford Online」頻道有多個年份的完整錄影（例如 2018 年秋季吳恩達版）。

**點評**：想走研究或需要扎實理論的人必修。需要線性代數、機率與多變數微積分基礎；建議先完成上方 Coursera 專項課程或數學課再挑戰。

---

## 3. Google 機器學習速成班（Machine Learning Crash Course, MLCC）

- **提供者**：Google
- **程度**：⭐ 入門～⭐⭐ 中級｜**費用**：免費｜**時長**：約 15 小時
- **連結**：<https://developers.google.com/machine-learning/crash-course>

**簡介**：Google 內部工程師培訓用的機器學習課程，2024 年 11 月全面改版，新增**大型語言模型與 AutoML** 等內容。包含互動式視覺化、超過 100 道練習題與 Colab 程式練習。

**你會學到**：線性與邏輯迴歸、分類評估指標、資料處理（數值與類別資料）、過擬合與正則化、神經網路、嵌入向量（Embeddings）、LLM 基礎、生產環境中的機器學習與公平性。

**點評**：節奏緊湊、互動性強，非常適合工程師在短時間內建立正確的機器學習觀念。只有測驗徽章，沒有正式證書。

---

## 4. Kaggle 微課程（Kaggle Learn）

- **提供者**：Kaggle（Google 旗下）
- **程度**：⭐～⭐⭐｜**費用**：免費，每門課完成可取得免費證書｜**時長**：每門約 3–5 小時
- **連結**：<https://www.kaggle.com/learn>

**簡介**：一系列短小、純實作的微課程，全部在瀏覽器中的 Notebook 完成，不需設定環境。

**推薦順序**：Python → Pandas → 機器學習入門（Intro to Machine Learning）→ 中級機器學習（Intermediate Machine Learning）→ 特徵工程（Feature Engineering）→ 深度學習入門（Intro to Deep Learning）→ 電腦視覺、時間序列等。

**點評**：「做中學」的最佳起點，學完即可參加 Kaggle 競賽累積作品。理論著墨少，建議搭配吳恩達的課程補足觀念。

---

## 5. 哈佛 CS50 人工智慧導論（CS50's Introduction to Artificial Intelligence with Python）

- **提供者**：哈佛大學（David J. Malan、Brian Yu）
- **程度**：⭐⭐ 中級｜**費用**：課程內容可透過 CS50 開放課程或 edX 免費學習；edX 認證證書需付費｜**時長**：約 7 週（每週 10–30 小時）
- **連結**：<https://cs50.harvard.edu/ai/>

**簡介**：以 Python 實作「傳統 AI + 機器學習」的完整導論，每週一個主題、搭配有趣的程式專案（如井字遊戲 AI、踩地雷推理、交通號誌辨識）。

**主題**：搜尋、知識表示、不確定性、最佳化、機器學習、神經網路、自然語言。

**先備條件**：CS50x 或具備 Python 程式經驗。

**點評**：專案設計極佳，能讓你真正寫出能運作的 AI 程式。涵蓋了許多深度學習課程不會教的經典 AI（搜尋、邏輯推理、約束滿足）。

---

## 6. 給初學者的機器學習（ML for Beginners）

- **提供者**：微軟（Microsoft Cloud Advocates）
- **程度**：⭐ 入門｜**費用**：免費開源｜**時長**：12 週、26 課，含測驗
- **連結**：<https://github.com/microsoft/ML-For-Beginners>

**簡介**：以 Scikit-learn 為主的**經典機器學習**課程（刻意不涵蓋深度學習），透過世界各地的資料集學習迴歸、分類、分群、自然語言處理、時間序列與強化學習入門。

**點評**：GitHub 上的課綱式教材，提供包含中文在內的多國語言翻譯，適合自學或教師作為授課素材。深度學習部分可接續同系列的 *AI for Beginners*（見 [03｜深度學習](03-deep-learning.md)）。

---

## 7. 機器學習與資料科學的數學（Mathematics for Machine Learning and Data Science Specialization）

- **提供者**：DeepLearning.AI，Luis Serrano 主講
- **程度**：⭐～⭐⭐｜**費用**：Coursera 首個模組可免費預覽，完整內容與證書需付費（可申請助學金）｜**時長**：3 門課，建議 12 週（每週約 5 小時）
- **連結**：<https://www.coursera.org/specializations/mathematics-for-machine-learning-and-data-science>

**課程組成**：線性代數、微積分、機率與統計（皆以機器學習應用為導向）。

**點評**：以視覺化與直觀解釋見長，適合「數學忘光了」想快速補回來的人。有評論認為深度偏淺，較適合作為複習或建立直覺，而非嚴謹的數學訓練。

---

## 8. 機器學習的數學（Mathematics for Machine Learning Specialization）

- **提供者**：倫敦帝國學院（Imperial College London）
- **程度**：⭐⭐ 中級｜**費用**：Coursera 首個模組可免費預覽，完整內容與證書需付費（可申請助學金）｜**時長**：3 門課，約 2–4 個月
- **連結**：<https://www.coursera.org/specializations/mathematics-machine-learning>

**課程組成**：線性代數、多變數微積分、主成分分析（PCA）。

**延伸**：同一團隊撰寫的教科書《Mathematics for Machine Learning》（Deisenroth、Faisal、Ong 著）可在 <https://mml-book.github.io/> 免費下載。

**點評**：比 DeepLearning.AI 版本更偏向數學推導，PCA 單元難度明顯較高。適合準備往研究或進階課程（如 CS229）發展的人。

---

## 9. 3Blue1Brown 數學視覺化系列

- **提供者**：Grant Sanderson（3Blue1Brown）
- **程度**：⭐ 入門｜**費用**：免費｜**語言**：英文，中文字幕普遍可得（B 站有官方中文頻道）
- **連結**：<https://www.3blue1brown.com/>

**推薦系列**：
- 線性代數的本質（Essence of Linear Algebra）
- 微積分的本質（Essence of Calculus）
- 神經網路系列（Neural Networks）：從反向傳播一路講到 Transformer 與注意力機制

**點評**：用動畫建立數學直覺的最佳資源，**強烈建議**在上任何數學或深度學習課程之前先看。

---

## 10. MIT 18.06 線性代數（Linear Algebra）

- **提供者**：MIT OpenCourseWare，Gilbert Strang 教授
- **程度**：⭐⭐｜**費用**：免費｜**時長**：一學期（34 講）
- **連結**：<https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/>

**點評**：史上最知名的線性代數公開課之一。若想更貼近資料科學應用，可接續 Strang 的 *18.065 Matrix Methods in Data Analysis, Signal Processing, and Machine Learning*。

---

## 11. StatQuest 統計與機器學習

- **提供者**：Josh Starmer
- **程度**：⭐ 入門｜**費用**：免費（YouTube）
- **連結**：<https://statquest.org/>

**點評**：以「把複雜的事講簡單」聞名，涵蓋統計檢定、決策樹、隨機森林、梯度提升、PCA、神經網路等。適合在其他課程卡住時查閱特定主題。

---

## 本類別選課建議

| 你的情況 | 建議組合 |
|---|---|
| 工程師、想快速上手 | Google MLCC → Kaggle Learn（機器學習系列） |
| 想要系統、扎實的入門 | 吳恩達 Machine Learning Specialization + Kaggle Learn 實作 |
| 數學基礎薄弱 | 3Blue1Brown → DeepLearning.AI 數學專項 |
| 準備走研究路線 | 帝國學院數學專項或 MIT 18.06 → CS229 |
| 喜歡專案驅動學習 | 哈佛 CS50 AI |
| 偏好中文 | 李宏毅「機器學習」、林軒田「機器學習基石」，見 [11｜中文原生課程](11-chinese-resources.md) |
