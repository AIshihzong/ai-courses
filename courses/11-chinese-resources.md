# 11｜中文原生課程與資源

> 適合對象：偏好以中文學習的讀者。
> 中文 AI 學習資源在 2024–2026 年快速成熟：台灣有李宏毅、林軒田等教授的經典公開課；中國大陸有李沐的《動手學深度學習》與 Datawhale 等開源社群的大量教程；政府與企業也提供許多免費入門課程。
> 本頁同時收錄**繁體與簡體**資源，簡體資源已在說明中標註。

[← 回到總覽](../README.md)

## 速覽

| # | 課程／資源 | 提供者 | 程度 | 費用 | 語言 |
|---|---|---|---|---|---|
| 1 | 生成式 AI 與機器學習系列課程 | 李宏毅（台大電機） | ⭐～⭐⭐⭐ | 免費 | 中文授課（台灣） |
| 2 | 機器學習基石／機器學習技法 | 林軒田（台大資工） | ⭐⭐～⭐⭐⭐ | 免費（台大開放式課程） | 中文授課、英文投影片 |
| 3 | 動手學深度學習 + 跟李沐學 AI | 李沐 | ⭐⭐ | 免費 | 簡體中文 |
| 4 | Datawhale 開源教程（Hello-Agents、Happy-LLM、Self-LLM 等） | Datawhale 社群 | ⭐～⭐⭐⭐ | 免費 | 簡體中文 |
| 5 | 面向開發者的大模型手冊（llm-cookbook） | Datawhale | ⭐～⭐⭐ | 免費 | 簡體中文 |
| 6 | CS 自學指南 | csdiy.wiki 社群 | — | 免費 | 簡體中文 |
| 7 | 政府免費 AI 學習平台 | 經濟部、人事行政總處、勞動部 | ⭐ | 免費 | 繁體中文 |
| 8 | 台灣人工智慧學校 | 台灣人工智慧學校基金會 | ⭐⭐～⭐⭐⭐ | 付費 | 繁體中文 |
| 9 | 飛槳 AI Studio | 百度 | ⭐～⭐⭐ | 免費為主 | 簡體中文 |
| 10 | 3Blue1Brown 中文頻道 | 3Blue1Brown 官方 | ⭐ | 免費 | 中文配音／字幕 |

---

## 1. 李宏毅：生成式 AI 與機器學習系列課程

- **提供者**：國立臺灣大學電機工程學系 李宏毅教授
- **程度**：⭐ 入門～⭐⭐⭐ 進階｜**費用**：免費（YouTube 公開）
- **連結**：課程網站 <https://speech.ee.ntu.edu.tw/~hylee/>｜YouTube <https://www.youtube.com/@HungyiLeeNTU>

**簡介**：華語圈最受歡迎的 AI 公開課。李宏毅教授以生動的比喻與動畫聞名，課程每年更新、緊跟前沿。

**主要課程**：

| 課程 | 學期 | 說明 | 連結 |
|---|---|---|---|
| 生成式人工智慧導論 | 2024 春 | 不需 AI 背景，聚焦生成式 AI 背後的概念與原理（不是教你怎麼用 ChatGPT） | <https://speech.ee.ntu.edu.tw/~hylee/genai/2024-spring.php> |
| 生成式 AI 時代下的機器學習 | 2025 春 | 從生成式 AI 的角度重新講解機器學習，涵蓋 LLM 訓練、推理、代理等 | 見課程網站 |
| 生成式 AI 與機器學習導論（Introduction to GenAI and ML） | 2025 秋 | 以 2024 生成式 AI 導論為基礎更新，加入機器學習與深度學習核心觀念，更重視概念與實作結合 | <https://speech.ee.ntu.edu.tw/~hylee/GenAI-ML/2025-fall.php> |
| 機器學習（Machine Learning） | 2021–2023 | 經典深度學習課程：CNN、自注意力、Transformer、GAN、自監督學習、強化學習等 | 見課程網站 |

**點評**：中文學習者的第一選擇。從零基礎通識到前沿研究都有，作業設計扎實（多在 Colab／Kaggle 上進行）。網路上有大量學習者整理的 HackMD 筆記可搭配閱讀。

---

## 2. 林軒田：機器學習基石／機器學習技法

- **提供者**：國立臺灣大學資訊工程學系 林軒田教授
- **程度**：⭐⭐ 中級～⭐⭐⭐ 進階｜**費用**：台大開放式課程（NTU OCW）免費觀看；Coursera 版自 2025 年中起僅首個模組可免費預覽
- **連結**：課程資源 <https://www.csie.ntu.edu.tw/~htlin/mooc/>｜台大開放式課程 <https://ocw.aca.ntu.edu.tw/>（搜尋「機器學習基石」）

**課程組成**：
- **機器學習基石（Machine Learning Foundations）**：學習問題、可學習性（VC 維度）、線性模型、過擬合、正則化、驗證等——著重「機器為什麼能學習」的理論
- **機器學習技法（Machine Learning Techniques）**：SVM 與核方法、集成學習（Bagging、AdaBoost、隨機森林、梯度提升）、神經網路與深度學習入門、矩陣分解等

**點評**：以中文授課、英文投影片，理論嚴謹，是華語圈公認最好的機器學習理論課之一。內容成形於 2013–2015 年，未涵蓋 LLM，但打下的理論基礎歷久彌新。

---

## 3. 李沐：動手學深度學習 + 跟李沐學 AI

- **提供者**：李沐（前 Amazon 首席科學家）等
- **程度**：⭐⭐ 中級｜**費用**：免費｜**語言**：簡體中文（另有英文版）
- **連結**：
  - 《動手學深度學習》中文版：<https://zh.d2l.ai/>
  - 論文精讀系列：<https://github.com/mli/paper-reading>
  - B 站頻道：搜尋「跟李沐學AI」

**簡介**：
- **《動手學深度學習》**：每一節都是可執行 Jupyter Notebook 的互動式教科書，被全球眾多大學採用。李沐在 B 站錄製了完整的中文配套課程（約 2021 年）。
- **論文精讀**：逐段精讀 AlexNet、ResNet、Transformer、BERT、GPT 系列、CLIP 等深度學習里程碑論文，是學習「如何讀論文」的絕佳示範。

**點評**：理論、數學與程式結合最好的中文深度學習教材。部分程式碼與框架版本較舊，建議以 PyTorch 版本為主。

---

## 4. Datawhale 開源教程系列

- **提供者**：Datawhale（中國大陸的開源 AI 學習社群）
- **程度**：⭐～⭐⭐⭐｜**費用**：免費開源｜**語言**：簡體中文
- **連結**：<https://github.com/datawhalechina>

**代表性教程**：

| 教程 | 說明 | GitHub 星數（2026 年 7 月快照） |
|---|---|---|
| **Hello-Agents**：從零開始構建智能體 | 智能體（AI 代理）原理與實踐，目標是讓讀者從 LLM 的「使用者」成為代理系統的「構建者」 | 約 6.5 萬 |
| **Happy-LLM**：從零開始的大語言模型原理與實踐 | 從 NLP 基礎、Transformer 到預訓練模型，以 PyTorch 手把手實作 LLaMA2 架構（含分詞器訓練與預訓練），另有 RAG 與 Agent 章節 | 約 3.2 萬 |
| **Self-LLM**：開源大模型食用指南 | 在 Linux 環境快速微調（全參數／LoRA）與部署國內外開源大模型與多模態大模型 | 約 3.1 萬 |
| **南瓜書（pumpkin-book）** | 周志華《機器學習》（西瓜書）的公式推導詳解 | — |

**點評**：中文開源 AI 教程的重鎮，內容新、實作多、社群活躍。三個 LLM 教程互相銜接：Self-LLM（應用部署）→ Happy-LLM（原理實作）→ Hello-Agents（代理）。

---

## 5. 面向開發者的大模型手冊（llm-cookbook）

- **提供者**：Datawhale
- **程度**：⭐～⭐⭐｜**費用**：免費｜**語言**：簡體中文
- **連結**：<https://github.com/datawhalechina/llm-cookbook>

**簡介**：將吳恩達與 DeepLearning.AI 的大模型系列短課（如給開發者的提示工程、以 LangChain 開發應用、建立 RAG 系統等）翻譯並重新整理成中文教材與 Notebook。

**點評**：想學 DeepLearning.AI 短課但英文吃力的讀者，可先讀中文版再回頭看原版影片。

---

## 6. CS 自學指南（csdiy.wiki）

- **提供者**：社群維護
- **費用**：免費｜**語言**：簡體中文
- **連結**：<https://csdiy.wiki/>

**簡介**：整理全球優質電腦科學公開課的中文索引，「深度學習」「機器學習」「機器學習系統」等分類收錄 CS229、CS224N、CS231n、CMU 深度學習系統等課程的介紹與學習資源連結。

**點評**：規劃自學路線時很好用的「課程地圖」，可與本倉庫互相參照。

---

## 7. 台灣政府免費 AI 學習平台

| 平台 | 主辦單位 | 說明 | 連結 |
|---|---|---|---|
| 中小企業網路大學校（AI 專區） | 經濟部 | AI 專區近 200 門課程，分為基礎知識、工具方法與實務應用 | <https://www.smelearning.org.tw/ai_zone.php> |
| e 等公務園＋學習平臺 | 行政院人事行政總處 | 公務人員線上學習平台，亦開放一般民眾註冊，有多門 AI 相關課程 | <https://elearn.hrd.gov.tw/> |
| 勞動力發展數位服務平台 | 勞動部勞動力發展署 | 職能培訓線上課程，含 AI 應用與數位技能 | <https://portal.wda.gov.tw/> |

**點評**：完全免費且多數可取得完課證明，適合想以中文入門、或需要時數證明的上班族與公務人員。內容以應用與通識為主，技術深度有限。

---

## 8. 台灣人工智慧學校（AI Academy）

- **提供者**：台灣人工智慧學校基金會
- **程度**：⭐⭐～⭐⭐⭐｜**費用**：付費
- **連結**：<https://aiacademy.tw/>

**簡介**：以在職人士為主的 AI 培訓機構，開設技術人才班、經理人班等實體與線上課程，強調產業實務專案。

**點評**：適合需要面對面教學、同儕交流與企業人脈的學習者；預算有限者可先從免費資源開始。

---

## 9. 飛槳 AI Studio

- **提供者**：百度
- **程度**：⭐～⭐⭐｜**費用**：免費為主（提供免費算力額度）｜**語言**：簡體中文
- **連結**：<https://aistudio.baidu.com/>

**點評**：中文課程與線上 Notebook 環境整合，提供 GPU 算力；課程多以百度 PaddlePaddle 框架示範。

---

## 10. 3Blue1Brown 中文頻道

- **提供者**：3Blue1Brown 官方（B 站）
- **程度**：⭐ 入門｜**費用**：免費
- **連結**：B 站搜尋「3Blue1Brown」

**點評**：線性代數、微積分與神經網路（含 Transformer）系列的官方中文版本，是建立數學直覺的最佳中文影片。

---

## 中文學習者的建議路線

```
零基礎通識          李宏毅「生成式 AI 導論 2024」或政府免費平台
      ↓
機器學習基礎        李宏毅「機器學習」＋ 林軒田「機器學習基石」（重理論者）
      ↓
深度學習            李沐《動手學深度學習》＋ B 站配套課程
      ↓
大型語言模型        李宏毅 2025 系列 → Datawhale Happy-LLM
      ↓
應用與代理          Datawhale llm-cookbook → Hello-Agents
```

> **提醒**：中文資源能大幅降低入門門檻，但 AI 領域最新的論文、文件與工具幾乎都以英文發布。建議在中文課程打好基礎後，逐步練習閱讀英文原文教材與官方文件；本倉庫其他分類中的英文課程皆附有中文介紹，可作為過渡。

---

## 延伸清單（2026 年 11 月增補）

以下把中文資源擴充為五個部分：台灣的大學課程、中國大陸的大學課程與開源教材、Datawhale 完整教程地圖、其他熱門開源專案，以及兩岸的學習平台與培訓機構。

### 一、台灣的大學公開課（續）

| 課程 | 授課者／學校 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| 生成式人工智慧與機器學習導論（2025 秋） | 李宏毅（台大） | ⭐～⭐⭐ | <https://speech.ee.ntu.edu.tw/~hylee/GenAI-ML/2025-fall.php> | 2025 年 12 月更新完畢；另有 AI Agent 相關講次，B 站有大量轉載與整理版 |
| 深度學習之應用（Applied Deep Learning） | 陳縕儂（台大資工） | ⭐⭐～⭐⭐⭐ | <https://www.csie.ntu.edu.tw/~miulab/> | 以 NLP 與 LLM 應用為主，作業紮實；錄影在 YouTube「Vivian NTU MiuLab」頻道 |
| 深度學習（CS565600） | 吳尚鴻（清華大學，新竹） | ⭐⭐⭐ | <https://nthu-datalab.github.io/ml/> | 英文講義＋中文授課錄影，理論與競賽式作業並重 |
| 深度生成模型（2025） | 陽明交通大學 | ⭐⭐⭐ | [YouTube](https://www.youtube.com/playlist?list=PLl6jkZVaP8zrR-UikQB-AXJyqpvGxMLGT) | 研究所課程公開錄影 |
| 人工智慧與深度學習 MOOC | 蔡炎龍（政治大學） | ⭐～⭐⭐ | <https://github.com/yenlung/Deep-Learning-MOOC> | 政大磨課師；神經網路、CNN、RNN，Notebook 已更新為 TensorFlow 2 |
| TAICA 聯盟課程 | 教育部 × 63 所大專院校 | ⭐～⭐⭐⭐ | <https://taicatw.net/> | 跨校選修的 AI 學程；115 學年上學期含成大「人工智慧導論」、清大「自然語言處理」、台大「機器學習」（林軒田）與「金融科技導論」等，部分課程以鏡像方式線上授課 |
| 台大／清大／陽明交大開放式課程 | 各校 | — | <https://ocw.aca.ntu.edu.tw/>・<https://ocw.nthu.edu.tw/>・<https://ocw.nycu.edu.tw/> | 線性代數、機率、演算法等先修課的中文錄影 |

### 二、中國大陸的大學課程與開源教材

| 課程／教材 | 學校／作者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| 大模型公開課（大模型交叉研討課） | 清華大學 劉知遠團隊 × OpenBMB | ⭐⭐ | [B 站](https://www.bilibili.com/video/BV1UG411p7zv/) | 9 大章、137 小節，從基礎到實戰 |
| 大模型基礎 | 浙江大學 LLM 團隊 | ⭐⭐ | <https://github.com/ZJU-LLMs/Foundations-of-LLMs> | 免費教材 PDF，六章並持續月更；每章附相關論文清單 |
| 動手學大模型 | 上海交通大學（張倬勝） | ⭐⭐ | <https://github.com/Lordog/dive-into-llms> | 由校內課程講義擴展的實作教程：微調與部署、提示學習、知識編輯、數學推理、GUI Agent、對齊與安全等；另有與華為昇騰合作的「大模型開發全流程」公益教程 |
| 大語言模型 | 中國人民大學（趙鑫等） | ⭐⭐ | <https://llmbook-zh.github.io/> | 由知名英文綜述擴寫的中文教材，免費下載 |
| 大規模語言模型：從理論到實踐 | 復旦大學（張奇等） | ⭐⭐ | <https://intro-llm.github.io/> | 訓練、微調、強化學習到部署 |
| 神經網路與深度學習（蒲公英書） | 復旦大學（邱錫鵬） | ⭐⭐ | <https://nndl.ai/> | 中文深度學習教科書；系列含通識版、案例與實踐、大模型與智能體 |
| 強化學習的數學原理 | 西湖大學（趙世鈺） | ⭐⭐ | <https://github.com/MathFoundationRL/Book-Mathematical-Foundation-of-Reinforcement-Learning> | 書與影片皆免費，中英文皆有 |
| 動手學強化學習 | 上海交通大學（張偉楠等） | ⭐⭐ | <https://hrl.boyuai.com/> | Notebook 式教材 |
| 智能計算系統 | 中國科學院大學（陳雲霽團隊） | ⭐⭐⭐ | <https://novel.ict.ac.cn/aics/> | AI 晶片、程式語言到框架的全棧課，B 站有錄影 |
| 機器學習系統：設計和實現 | OpenMLSys 社群 | ⭐⭐⭐ | <https://openmlsys.github.io/> | 開源教材 |
| 人工智能：模型與算法 | 浙江大學（吳飛） | ⭐⭐ | <https://www.icourse163.org/> （搜尋課名） | 中國大學 MOOC 上的國家級精品課 |
| 人工智能綜合能力提升培訓 2026 系列 | 國家高等教育智慧教育平台 | ⭐ | <https://www.chinaooc.com.cn/ai2026> | 人工智能入門、人工智能導論、面向人文社科的導論、創新項目設計、技術與應用等通識慕課 |
| 微軟 AI 教育與學習共建社區（AI-EDU） | 微軟亞洲研究院 | ⭐～⭐⭐ | <https://github.com/microsoft/ai-edu> | 神經網路基本原理簡明教程與實踐案例 |
| 推薦系統／搜尋引擎／深度強化學習公開課 | 王樹森 | ⭐⭐ | <https://github.com/wangshusen/RecommenderSystem> | 工業界視角的系列中文課程 |

### 三、Datawhale 教程地圖

Datawhale 的開源教程數量眾多，依學習階段整理如下（皆為簡體中文、免費）。官方另有[人工智能培養方案](https://www.datawhale.cn/learn/summary/40)可作為總路線。

| 階段 | 教程 | 連結 | 內容 |
|---|---|---|---|
| 基礎 | Joyful Pandas | <https://github.com/datawhalechina/joyful-pandas> | Pandas 資料處理 |
| 基礎 | 南瓜書 | <https://github.com/datawhalechina/pumpkin-book> | 西瓜書公式推導 |
| 基礎 | 深度學習詳解（LeeDL Tutorial，蘋果書） | <https://github.com/datawhalechina/leedl-tutorial> | 李宏毅課程文字版 |
| 基礎 | 深入淺出 PyTorch | <https://github.com/datawhalechina/thorough-pytorch> | PyTorch 由淺入深 |
| 基礎 | Easy RL（蘑菇書） | <https://github.com/datawhalechina/easy-rl> | 強化學習 |
| LLM 原理 | Base LLM：從 NLP 到 LLM 的算法全棧教程 | <https://github.com/datawhalechina/base-llm> | 從傳統 NLP 一路到大語言模型 |
| LLM 原理 | Happy-LLM | <https://github.com/datawhalechina/happy-llm> | 從零實作語言模型 |
| LLM 原理 | 動手學 LLM（LLMs From Scratch 中文版） | <https://github.com/datawhalechina/llms-from-scratch-cn> | 從零構建 GLM4、Llama3、RWKV6 |
| LLM 原理 | Tiny-Universe：大模型白盒子構建指南 | <https://github.com/datawhalechina/tiny-universe> | 手寫擴散模型、LLM、RAG、Agent 與評測 |
| LLM 原理 | 大模型基礎（So-Large-LM） | <https://github.com/datawhalechina/so-large-lm> | 理論到實戰的知識體系 |
| 應用開發 | LLM Universe：動手學大模型應用開發 | <https://github.com/datawhalechina/llm-universe> | 面向小白：呼叫 API、搭建知識庫、建立 RAG 應用並部署 |
| 應用開發 | All-in-RAG | <https://github.com/datawhalechina/all-in-rag> | RAG 技術全棧指南，含多模態檢索與工程化 |
| 應用開發 | llm-cookbook | <https://github.com/datawhalechina/llm-cookbook> | 吳恩達大模型系列短課中文版 |
| 應用開發 | Self-LLM：開源大模型食用指南 | <https://github.com/datawhalechina/self-llm> | 開源模型的部署與微調 |
| 應用開發 | Unlock-HF | <https://github.com/datawhalechina/unlock-hf> | Hugging Face 生態系教程 |
| 應用開發 | Handy Ollama | <https://github.com/datawhalechina/handy-ollama> | 本機部署大模型；2025 年 11 月被 Ollama 官方倉庫收錄為教學 |
| 代理 | Hello-Agents | <https://github.com/datawhalechina/hello-agents> | 從零開始構建智能體 |
| 代理 | wow-agent | <https://github.com/datawhalechina/wow-agent> | 適合企業內部署的簡易 Agent 教程 |
| 代理 | Agentic AI 中文版 | <https://github.com/datawhalechina/agentic-ai> | 吳恩達 Agentic AI 課程的翻譯與解讀 |
| 代理 | Agent Skills 中文版 | <https://github.com/datawhalechina/agent-skills-with-anthropic> | DeepLearning.AI × Anthropic 短課的中文整理 |
| 無程式碼 | Handy n8n | <https://github.com/datawhalechina/handy-n8n> | n8n 自動化工作流程 |
| Vibe Coding | Easy-Vibe | <https://github.com/datawhalechina/easy-vibe> | Vibe Coding 產品實戰，支援 10 種語言 |
| Vibe Coding | Vibe Vibe | <https://github.com/datawhalechina/vibe-vibe> | 零基礎 AI 編程指南 |
| 專題 | FunRec（小麥書） | <https://github.com/datawhalechina/fun-rec> | 推薦系統 |
| 專題 | Every Embodied | <https://github.com/datawhalechina/every-embodied> | 具身智慧 |

### 四、其他熱門中文開源專案

| 專案 | 作者 | 連結 | 說明 |
|---|---|---|---|
| MiniMind | jingyaogong | <https://github.com/jingyaogong/minimind> | 從零訓練 64M 小語言模型的完整鏈路，約 2 小時、成本極低；另有視覺與多模態版本 |
| llm-action | liguodongiot | <https://github.com/liguodongiot/llm-action> | 大模型技術原理與實戰經驗分享（訓練、微調、推論、部署） |
| awesome-LLM-resources | WangRongsheng | <https://github.com/WangRongsheng/awesome-LLM-resources> | 中文 LLM 資源總表 |
| 吳恩達課程中文筆記 | 黃海廣 | <https://github.com/fengdu78/Coursera-ML-AndrewNg-Notes> | 經典機器學習課的中文筆記；另有[深度學習專項筆記](https://github.com/fengdu78/deeplearning_ai_books) |
| 20 天吃掉那隻 PyTorch | lyhue1991 | <https://github.com/lyhue1991/eat_pytorch_in_20_days> | 以 20 天為單位的 PyTorch 自學計畫 |
| PyTorch 中文手冊 | zergtant | <https://github.com/zergtant/pytorch-handbook> | PyTorch 入門中文教程 |
| 《深度學習》花書中文翻譯 | exacity 社群 | <https://github.com/exacity/deeplearningbook-chinese> | Goodfellow 等《Deep Learning》的社群翻譯 |
| 鳶尾花書 | 薑偉生 | <https://github.com/Visualize-ML> | 數學與機器學習視覺化系列叢書 |
| 論文精讀 | 李沐 | <https://github.com/mli/paper-reading> | 深度學習里程碑論文的逐段講解 |

### 五、學習平台與培訓機構

**台灣**

| 平台 | 性質 | 連結 | 說明 |
|---|---|---|---|
| edu 磨課師＋ | 教育部免費平台 | <https://moocs.moe.edu.tw/> | 整合各大學磨課師；2026 年 9 月推薦 18 門 AI 課程 |
| ewant 育網／OpenEdu／TaiwanLIFE | 大學聯盟磨課師平台 | <https://www.ewant.org/>・<https://www.openedu.tw/>・<https://taiwanlife.org/> | 多數免費，部分提供修課證明 |
| 工研院產業學習網 | 法人培訓（付費，部分補助） | <https://college.itri.org.tw/> | 含生成式 AI 工程師培訓班 |
| 資策會數位教育研究所 | 法人培訓（付費，部分補助） | <https://www.iiiedu.org.tw/> | 結合考照的 AI 應用課程 |
| 台灣大哥大免費 AI 課程 | 企業公益 | <https://www.taiwanmobile.com/content/event/consumer-ai/index.html> | 線上與門市實體場次 |
| Hahow 好學校／TibaMe／六角學院／ALPHA Camp | 商業線上課程 | <https://hahow.in/>・<https://www.tibame.com/>・<https://www.hexschool.com/>・<https://tw.alphacamp.co/> | 付費；中文講師、在地案例，品質依課程而異 |
| iT 邦幫忙鐵人賽 | 社群技術文章 | <https://ithelp.ithome.com.tw/> | 每年有大量繁體中文的 30 天 AI 主題系列文 |

**中國大陸**

| 平台 | 性質 | 連結 | 說明 |
|---|---|---|---|
| 中國大學 MOOC／學堂在線 | 大學慕課平台 | <https://www.icourse163.org/>・<https://www.xuetangx.com/> | 各校 AI 通識與專業課，多數免費 |
| 國家高等教育智慧教育平台 | 教育部 | <https://higher.smartedu.cn/> | 設有「人工智能 2026」專題 |
| 阿里雲認證與培訓中心 | 企業 | <https://edu.aliyun.com/> | 免費課程與大模型 ACA／ACP 認證（見 [12](12-certifications.md)） |
| 魔搭 ModelScope | 模型社群 | <https://www.modelscope.cn/> | 模型、資料集與學習資源 |
| 華為人才在線 | 企業 | <https://e.huawei.com/cn/talent/> | HCIA／HCIP-AI 認證課程 |
| 阿里雲天池／和鯨社區 | 競賽與實作 | <https://tianchi.aliyun.com/>・<https://www.heywhale.com/> | 競賽、資料集與線上 Notebook |
| 極客時間／深藍學院 | 商業課程 | <https://time.geekbang.org/>・<https://www.shenlanxueyuan.com/> | 付費；前者偏工程實戰營，後者偏機器人、自動駕駛與具身智慧 |

> **選擇中文付費課程的提醒**：市面上「大模型速成」「AI 副業」類課程眾多且價差極大。報名前先確認：講師是否有可查證的實務或研究背景、課綱是否涵蓋評估與上線、是否能試聽、退費規則為何。多數內容其實可在上面的免費開源教程中找到。
