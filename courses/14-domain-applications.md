# 14｜垂直領域與專題課程

> 適合對象：已有機器學習基礎，想把 AI 用在特定領域（醫療、科學、金融、邊緣裝置、資安……），或想補足某個專題（圖神經網路、因果推論、推薦系統、時間序列……）的人。
> 通用課程教的是方法，真正的價值往往出現在「方法 × 領域知識」的交會處。本頁依專題與產業整理。

[← 回到總覽](../README.md)

> 程度：⭐ 入門｜⭐⭐ 中級｜⭐⭐⭐ 進階　　費用：未特別註明者為免費

## 目錄

- [A. 方法專題](#a-方法專題)：圖機器學習、機率與貝氏、因果推論、時間序列、推薦與搜尋、以資料為中心的 AI
- [B. 邊緣 AI 與高效推論](#b-邊緣-ai-與高效推論)
- [C. AI 資安與紅隊演練](#c-ai-資安與紅隊演練)
- [D. AI for Science：生醫、化學、物理、氣候](#d-ai-for-science生醫化學物理氣候)
- [E. 醫療與健康照護](#e-醫療與健康照護)
- [F. 金融](#f-金融)
- [G. 其他領域](#g-其他領域)：法律、設計與 UX、遊戲與 3D、語音、量子、神經科學

---

## A. 方法專題

### 圖機器學習（Graph ML）

| 課程（中文／英文） | 提供者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| 圖機器學習 / CS224W: Machine Learning with Graphs | 史丹佛（Jure Leskovec） | ⭐⭐⭐ | <https://web.stanford.edu/class/cs224w/> | 圖神經網路、知識圖譜、圖生成模型的標準課程，錄影與作業公開 |
| 幾何深度學習 / Geometric Deep Learning | AMMI（Bronstein 等） | ⭐⭐⭐ | <https://geometricdeeplearning.com/> | 以對稱性統一 CNN、GNN、Transformer 的理論視角 |
| 深度圖學習 / Deep Graph Learning（2025） | 倫敦帝國學院（Islem Rekik） | ⭐⭐⭐ | [YouTube](https://www.youtube.com/playlist?list=PLug43ldmRSo14Y_vt7S6vanPGh-JpHR7T) | 較新的完整錄影 |

### 機率、貝氏與因果推論

| 課程（中文／英文） | 提供者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| 統計再思考 / Statistical Rethinking | Richard McElreath | ⭐⭐ | <https://github.com/rmcelreath/stat_rethinking_2024> | 貝氏統計與因果思維的名課，完整影片與教材免費 |
| 機率機器學習 / Probabilistic Machine Learning | 圖賓根大學（Philipp Hennig） | ⭐⭐⭐ | [YouTube](https://www.youtube.com/playlist?list=PL05umP7R6ij2YE8rRJSb-olDNbntAQ_Bx) | 高斯過程、圖模型、變分推論 |
| 機率圖模型專項課程 / Probabilistic Graphical Models | 史丹佛（Daphne Koller），Coursera | ⭐⭐⭐ | <https://www.coursera.org/specializations/probabilistic-graphical-models> | 部分免費；經典但難度高 |
| 因果推論導論 / Introduction to Causal Inference | Brady Neal | ⭐⭐ | <https://www.bradyneal.com/causal-inference-course> | 從機器學習角度講因果，影片＋免費教科書 |
| 給勇者的因果推論 / Causal Inference for the Brave and True | Matheus Facure | ⭐⭐ | <https://matheusfacure.github.io/python-causality-handbook/> | Python 實作導向的免費線上書 |

### 時間序列

| 課程（中文／英文） | 提供者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| 預測：原理與實務 / Forecasting: Principles and Practice | Hyndman & Athanasopoulos | ⭐⭐ | <https://otexts.com/fpp3/> | 時間序列預測的免費標準教科書（R 版）；另有 [Python 版](https://otexts.com/fpppy/) |
| 時間序列 / Time Series | Kaggle Learn | ⭐⭐ | <https://www.kaggle.com/learn> | 微課程，含混合模型與預測實作 |

### 推薦系統與搜尋

| 課程（中文／英文） | 提供者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| 推薦系統 / Recommendation Systems | Google | ⭐⭐ | <https://developers.google.com/machine-learning/recommendation> | 候選生成、評分、重排的精簡課程 |
| 推薦系統專項課程 / Recommender Systems Specialization | 明尼蘇達大學，Coursera | ⭐⭐ | <https://www.coursera.org/specializations/recommender-systems> | 部分免費；協同過濾到評估方法 |
| 推薦系統公開課 | 王樹森 | ⭐⭐ | <https://github.com/wangshusen/RecommenderSystem> | **中文**；工業界推薦系統全流程（召回、排序、重排、冷啟動） |
| 深度推薦演算法實踐（FunRec／小麥書） | Datawhale | ⭐⭐ | <https://github.com/datawhalechina/fun-rec> | **中文**；從級聯架構到生成式推薦 |
| 資訊檢索導論 / Introduction to Information Retrieval | Manning、Raghavan、Schütze | ⭐⭐ | <https://nlp.stanford.edu/IR-book/> | 搜尋引擎與檢索理論的免費教科書，RAG 的理論根基 |

### 以資料為中心的 AI

| 課程（中文／英文） | 提供者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| 以資料為中心的 AI 導論 / Introduction to Data-Centric AI | MIT | ⭐⭐ | <https://dcai.csail.mit.edu/> | 標註錯誤偵測、資料集偏移、資料整理；影片、講義與實作全公開 |
| 資料工程 Zoomcamp / Data Engineering Zoomcamp | DataTalksClub | ⭐⭐ | <https://github.com/DataTalksClub/data-engineering-zoomcamp> | 資料管線、資料倉儲、串流，社群梯次制 |
| 資料工程專業證書 / Data Engineering Professional Certificate | DeepLearning.AI × AWS，Coursera | ⭐⭐ | <https://www.deeplearning.ai/courses/data-engineering/> | 付費；Joe Reis 主講 |

---

## B. 邊緣 AI 與高效推論

把模型壓小、跑在手機、微控制器或個人電腦上。隨著小型語言模型（SLM）進步，這個方向的課程在 2025–2026 年明顯增加。

| 課程（中文／英文） | 提供者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| TinyML 與高效深度學習運算 / MIT 6.5940 | MIT（韓松） | ⭐⭐⭐ | <https://hanlab.mit.edu/courses/2024-fall-65940> | 量化、剪枝、神經架構搜尋、LLM 與擴散模型的高效推論；5 個實驗 |
| 機器學習系統（開源教科書）/ Machine Learning Systems | 哈佛（CS249r） | ⭐⭐～⭐⭐⭐ | <https://mlsysbook.ai/> | 從嵌入式裝置到資料中心的 ML 系統工程，附實驗 |
| TinyML 專業證書 / Tiny Machine Learning Professional Certificate | 哈佛 × Google，edX | ⭐⭐ | <https://www.edx.org/> （搜尋 "TinyML"） | 可旁聽；在微控制器上部署模型 |
| 嵌入式機器學習導論 / Introduction to Embedded Machine Learning | Edge Impulse，Coursera | ⭐～⭐⭐ | <https://www.coursera.org/learn/introduction-to-embedded-machine-learning> | 部分免費；動手導向 |
| 給初學者的邊緣 AI / EdgeAI for Beginners | 微軟 | ⭐～⭐⭐ | <https://github.com/microsoft/edgeai-for-beginners> | 小型語言模型、模型最佳化與本機部署，含多國語言翻譯 |
| Phi 實戰手冊 / Phi Cookbook | 微軟 | ⭐⭐ | <https://github.com/microsoft/PhiCookBook> | 微軟 Phi 系列小模型的實作範例集 |
| 裝置端 AI 導論 / Introduction to On-Device AI | DeepLearning.AI × Qualcomm | ⭐⭐ | <https://www.deeplearning.ai/short-courses/introduction-to-on-device-ai/> | 短課；模型轉換、量化、裝置部署 |
| 機器學習編譯 / Machine Learning Compilation | 陳天奇（MLC） | ⭐⭐⭐ | <https://mlc.ai/> | 以 Apache TVM 為例講解模型編譯與部署；有[中文版](https://mlc.ai/zh/) |
| 動手學 Ollama / Handy Ollama | Datawhale | ⭐ | <https://github.com/datawhalechina/handy-ollama> | **中文**；用 CPU 在本機部署大模型 |

---

## C. AI 資安與紅隊演練

LLM 應用帶來提示注入、資料外洩、代理越權等新型風險，「AI 紅隊」成為新興專業。

| 課程／資源（中文／英文） | 提供者 | 程度 | 費用 | 連結 | 說明 |
|---|---|---|---|---|---|
| AI 紅隊 101 / AI Red Teaming 101 | 微軟 | ⭐⭐ | 免費 | <https://learn.microsoft.com/security/ai-red-team/training> | 微軟 AI 紅隊團隊製作的系列教學 |
| AI 紅隊演練場 / AI Red Teaming Playground Labs | 微軟 | ⭐⭐ | 免費 | <https://github.com/microsoft/AI-Red-Teaming-Playground-Labs> | 可自行架設的攻防練習關卡 |
| LLM 應用的紅隊測試 / Red Teaming LLM Applications | DeepLearning.AI × Giskard | ⭐⭐ | 免費 | <https://www.deeplearning.ai/short-courses/red-teaming-llm-applications/> | 1–2 小時短課，含自動化紅隊工具 |
| Web LLM 攻擊 / Web LLM Attacks | PortSwigger Web Security Academy | ⭐⭐ | 免費 | <https://portswigger.net/web-security/llm-attacks> | 含線上實驗室的互動教材 |
| AI 紅隊學習路徑 / AI Red Teamer Path | Hack The Box × Google | ⭐⭐～⭐⭐⭐ | 部分付費 | <https://academy.hackthebox.com/> | 對應 Google 安全 AI 框架（SAIF）的職務路徑 |
| AI 紅隊課程 / AI Red Teaming | Learn Prompting（HackAPrompt 團隊） | ⭐⭐～⭐⭐⭐ | 付費（大師班約 1,199 美元） | <https://learnprompting.org/> | 由舉辦全球提示攻擊競賽的團隊授課 |
| LLM 應用十大風險 / OWASP Top 10 for LLM Applications | OWASP GenAI Security Project | ⭐⭐ | 免費 | <https://genai.owasp.org/> | 業界通用的風險清單與防護指引 |
| MITRE ATLAS | MITRE | ⭐⭐ | 免費 | <https://atlas.mitre.org/> | AI 系統攻擊手法知識庫 |
| Gandalf 提示注入闖關 | Lakera | ⭐ | 免費 | <https://gandalf.lakera.ai/> | 用遊戲理解提示注入 |
| 探索對抗式機器學習 / Exploring Adversarial Machine Learning | NVIDIA DLI | ⭐⭐⭐ | 付費 | <https://www.nvidia.com/en-us/training/> | NVIDIA AI 紅隊開設 |

相關認證（CompTIA SecAI+、ISACA AAISM 等）見 [12｜認證](12-certifications.md)；AI 對齊與治理見 [10｜AI 安全](10-ai-safety-ethics.md)。

---

## D. AI for Science：生醫、化學、物理、氣候

| 課程（中文／英文） | 提供者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| AlphaFold 實務指南 / AlphaFold: A Practical Guide | EMBL-EBI × Google DeepMind | ⭐⭐ | <https://www.ebi.ac.uk/training/online/courses/alphafold/> | 蛋白質結構預測工具的官方線上教學 |
| 生命科學中的深度學習 / MIT 6.874 | MIT（Manolis Kellis） | ⭐⭐⭐ | <https://mit6874.github.io/> | 基因體學、蛋白質、影像 |
| 生物資訊的機器學習 / CS 582（2024 秋） | UIUC | ⭐⭐⭐ | [YouTube](https://www.youtube.com/playlist?list=PLIygTcviGPKBtxPX875Z8suCYGJkrPQ2Z) | 完整錄影 |
| 分子與材料的深度學習 / Deep Learning for Molecules and Materials | Andrew White | ⭐⭐～⭐⭐⭐ | <https://dmol.pub/> | 免費線上教科書，含圖神經網路與等變模型 |
| AI 與資料科學在科學上的應用 / EE292R | 史丹佛 | ⭐⭐ | [Stanford Online](https://www.youtube.com/stanfordonline) | 2026 秋季講座系列 |
| 平行運算與科學機器學習 / MIT 18.337J | MIT（Chris Rackauckas） | ⭐⭐⭐ | <https://book.sciml.ai/> | 物理資訊神經網路、可微分程式設計 |
| 資料驅動的科學與工程 / Data-Driven Science and Engineering | Steve Brunton、Nathan Kutz | ⭐⭐～⭐⭐⭐ | <https://www.databookuw.com/> | 教科書與大量 YouTube 影片；動力系統、控制與 ML |
| 氣候科學的計算工具 / Computational Tools for Climate Science | Neuromatch（Climatematch） | ⭐⭐ | <https://neuromatch.io/courses/> | 每年 7 月的線上梯次課程，教材公開 |
| 氣候變遷 AI 資源 / Climate Change AI | Climate Change AI | ⭐⭐ | <https://www.climatechange.ai/> | 暑期學校錄影、教學與論文導讀 |

---

## E. 醫療與健康照護

| 課程（中文／英文） | 提供者 | 程度 | 費用 | 連結 | 說明 |
|---|---|---|---|---|---|
| 醫療中的 AI 專項課程 / AI in Healthcare Specialization | 史丹佛醫學院，Coursera | ⭐～⭐⭐ | 部分免費 | <https://www.coursera.org/specializations/ai-healthcare> | 5 門課：醫療體系、臨床資料、ML 基礎、評估與落地 |
| 醫學 AI 專項課程 / AI for Medicine Specialization | DeepLearning.AI，Coursera | ⭐⭐ | 部分免費 | <https://www.coursera.org/specializations/ai-for-medicine> | 3 門課：診斷、預後、治療；偏技術實作 |
| 醫療機器學習 / MIT 6.S897 | MIT | ⭐⭐⭐ | 免費 | <https://ocw.mit.edu/courses/6-s897-machine-learning-for-healthcare-spring-2019/> | 研究所課程（2019） |
| 健康照護中的 AI：從策略到落地 / AI in Health Care: From Strategies to Implementation | 哈佛醫學院高階教育 | ⭐⭐ | 付費（約 3,000 美元，8 週） | <https://learn.hms.harvard.edu/> | 給醫療機構主管與決策者 |

> 醫療 AI 特別重視**驗證、偏誤與法規**。選課時留意是否涵蓋臨床驗證設計與資料隱私，而不只是模型準確率。

---

## F. 金融

| 課程（中文／英文） | 提供者 | 程度 | 費用 | 連結 | 說明 |
|---|---|---|---|---|---|
| 交易的機器學習 / Machine Learning for Trading（CS 7646） | 喬治亞理工 | ⭐⭐ | 教材公開 | <https://lucylabs.gatech.edu/ml4t/> | OMSCS 熱門課的公開教材 |
| 應用 AI 實驗室 / Applied AI Lab | WorldQuant University | ⭐⭐ | 免費 | <https://www.wqu.edu/> | 免費的專案式課程，另有免費的金融工程碩士 |
| 金融中的機器學習與強化學習專項課程 / ML and RL in Finance | 紐約大學，Coursera | ⭐⭐⭐ | 部分免費 | <https://www.coursera.org/specializations/machine-learning-reinforcement-finance> | 數學要求高 |
| 投資專業人士資料科學證書 / Data Science for Investment Professionals Certificate | CFA 協會 | ⭐⭐ | 付費 | <https://www.cfainstitute.org/> | 給金融從業人員的資料科學與 ML 證書 |

---

## G. 其他領域

| 領域 | 課程（中文／英文） | 提供者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|---|
| 法律 | AI 與法律 / AI & Law | 隆德大學，Coursera | ⭐ | <https://www.coursera.org/learn/ai-law> | 部分免費；AI 在法律實務與規範中的議題 |
| 設計與 UX | 人與 AI 指南 / People + AI Guidebook | Google PAIR | ⭐ | <https://pair.withgoogle.com/guidebook/> | 設計 AI 產品的準則與工作坊素材 |
| 設計與 UX | AI 應用的 UX 設計（第 12 課） | 微軟 Generative AI for Beginners | ⭐ | <https://github.com/microsoft/generative-ai-for-beginners> | 信任、透明度與回饋機制 |
| 遊戲 | 遊戲的機器學習 / ML for Games Course | Hugging Face | ⭐⭐ | <https://huggingface.co/learn/ml-games-course> | 把 AI 模型整合進 Unity 等遊戲流程（官方已不再新增單元） |
| 3D | 3D 的機器學習 / ML for 3D Course | Hugging Face | ⭐⭐ | <https://huggingface.co/learn/ml-for-3d-course> | 生成式 3D、高斯潑濺（Gaussian Splatting） |
| 3D | 3D 資料的機器學習 / Machine Learning for 3D Data | KAIST | ⭐⭐⭐ | <https://3dml.kaist.ac.kr/> | 研究所課程，2026 春季 |
| 語音 | 口語語言處理 / CS224S: Spoken Language Processing | 史丹佛 | ⭐⭐⭐ | <https://web.stanford.edu/class/cs224s/> | 語音辨識、合成與對話系統 |
| 量子 | 量子機器學習教材 / Xanadu Quantum Codebook | Xanadu | ⭐⭐ | <https://codebook.xanadu.ai/> | 互動式量子運算與量子 ML 入門 |
| 神經科學 | 計算神經科學／NeuroAI | Neuromatch Academy | ⭐⭐～⭐⭐⭐ | <https://neuromatch.io/courses/> | 每年 7 月梯次，教材公開；學費依所在國家生活成本調整 |
| 具身智慧 | 人人都能學的具身智慧（Every Embodied） | Datawhale | ⭐⭐ | <https://github.com/datawhalechina/every-embodied> | **中文**；機器人與具身 AI 入門，更多見 [08](08-reinforcement-learning.md) |

---

## 選課建議

1. **先確認通用基礎**：多數領域課程預設你已會 Python 與基本機器學習（[02](02-ml-foundations.md)、[03](03-deep-learning.md)）。
2. **領域知識比模型重要**：在醫療、金融、科學領域，懂資料怎麼來、指標代表什麼，比換一個更新的模型有用得多。
3. **找得到真實資料集的課優先**：能讓你實際接觸領域資料（醫學影像、分子、財報、感測器）的課程，學習效果遠勝只講概念的課。
