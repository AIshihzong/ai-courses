# AI 課程大全：全網 AI 課程中文整理與分析

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/AIshihzong/ai-courses)](https://github.com/AIshihzong/ai-courses/commits)

> 一份**有點評、有路線、有查核**的 AI 學習地圖：從全球各大平台、頂尖大學、AI 公司官方學院、開源社群與中文世界蒐集約 550 項 AI 課程與學習資源，全部以**繁體中文**翻譯、介紹與點評。

**和其他課程清單有什麼不同？**

- **不只是連結**：每門精選課程都有中文簡介、學習重點與優缺點點評，並告訴你該先上哪一門
- **依身分找起點**：上班族、主管、教師、工程師、研究者各有對應的入口與 7 條學習路線
- **資訊夠新**：更新至 2026 年 11 月，涵蓋 AI 代理、MCP、上下文工程、各家認證改版
- **可信度透明**：111 個 GitHub 連結逐一驗證；無法查證的價格與日期一律標註「以官方為準」

**English** — A curated map of ~550 AI learning resources (courses, open textbooks, university lectures, channels) plus 30+ certifications, written in Traditional Chinese with a short review of each featured course. It covers 22 categories from AI literacy to LLM training, agents, MLOps and AI safety, and includes learning paths, a platform directory and a 2026 trend analysis. Course titles keep their English names, so the tables are usable even if you do not read Chinese.

**简体中文** — 一份带点评的 AI 学习地图：收录约 550 项 AI 课程与学习资源、30 多项认证，分为 22 个类别，并附 7 条学习路线、平台总览与 2026 年趋势分析。正文为繁体中文，课程名称保留英文原名，简体读者可直接阅读。

- **收錄規模**：22 個分類、850 多筆條目；扣除跨分類重複後約 **550 項不重複資源**（課程、開源教材、免費教科書、頻道與社群），另含 **30 多項 AI 認證**
- **資料整理日期**：2026 年 11 月 10 日（第二版；初版為 2026 年 10 月 13 日，見[更新紀錄](#更新紀錄)）
- **查核方式**：文中 111 個 GitHub 課程倉庫連結已逐一驗證存在，主要課程的課綱直接取自官方倉庫；其餘資訊來自官方頁面與多方搜尋比對，二手資料已標註「以官方為準」
- **翻譯原則**：課程名稱以「中文譯名／英文原名」並列；除官方已有中文名稱者外，中文譯名為本倉庫意譯，**搜尋課程時請使用英文原名**

---

## 快速開始

**不知道從哪裡開始？** 依你的身分挑一個起點：

| 我是… | 從這裡開始 | 下一步 |
|---|---|---|
| 完全沒接觸過 AI 的上班族 | [Elements of AI](courses/01-ai-literacy.md#1-人工智慧要素elements-of-ai) 或 [李宏毅「生成式 AI 導論」](courses/11-chinese-resources.md#1-李宏毅生成式-ai-與機器學習系列課程) | [路線 A：職場 AI 應用者](docs/learning-paths.md#路線-a職場-ai-應用者) |
| 主管、創業者、產品經理 | [商業、產品與領導者課程](courses/15-business-leadership.md) | [AI 安全與治理](courses/10-ai-safety-ethics.md) |
| 教師、家長、學生 | [教育工作者、K-12 與青少年](courses/16-educators-k12.md) | [AI 通識](courses/01-ai-literacy.md) |
| 不寫程式但想做出工具 | [無程式碼、Vibe Coding 與創意 AI](courses/17-nocode-creative.md) | [先修：程式基礎](courses/18-prerequisites.md) |
| 想做 AI 應用的軟體工程師 | [微軟 Generative AI for Beginners](courses/05-generative-ai-apps.md#4-給初學者的生成式-aigenerative-ai-for-beginners) | [路線 B：AI 應用工程師](docs/learning-paths.md#路線-bai-應用工程師) |
| 想打造 AI 代理的開發者 | [吳恩達 Agentic AI](courses/06-ai-agents.md#1-代理式-aiagentic-ai) | [路線 C：AI 代理工程師](docs/learning-paths.md#路線-cai-代理工程師) |
| 想真正懂原理的學生／工程師 | [吳恩達 ML 專項](courses/02-ml-foundations.md#1-機器學習專項課程machine-learning-specialization) 或 [Karpathy Zero to Hero](courses/03-deep-learning.md#4-神經網路從零到英雄neural-networks-zero-to-hero) | [路線 D：ML／DL 扎根](docs/learning-paths.md#路線-d機器學習深度學習扎根) |
| 想照名校課表自學 | [大學公開課總覽](courses/13-university-courses.md) | [免費教科書](courses/19-books.md) |
| 想做模型訓練或研究 | [史丹佛 CS336](courses/04-nlp-llm.md#2-史丹佛-cs336從零打造語言模型cs336-language-modeling-from-scratch) | [路線 E：LLM 研究與模型訓練](docs/learning-paths.md#路線-ellm-研究與模型訓練) |
| 偏好全中文學習 | [中文原生課程與資源](courses/11-chinese-resources.md) | [路線 G：全中文學習路線](docs/learning-paths.md#路線-g全中文學習路線) |

---

## 課程分類目錄

### 核心技術主題（每類含精選詳解＋延伸清單）

| # | 分類 | 條目數 | 內容 | 首推 |
|---|---|---|---|---|
| 01 | [AI 通識與入門](courses/01-ai-literacy.md) | 19 | 非技術背景也能上的 AI 素養課 | Elements of AI |
| 02 | [機器學習基礎與數學](courses/02-ml-foundations.md) | 34 | 經典機器學習與必備數學 | 吳恩達 ML 專項、Google MLCC |
| 03 | [深度學習](courses/03-deep-learning.md) | 26 | 神經網路原理與實作 | fast.ai、Karpathy Zero to Hero |
| 04 | [自然語言處理與大型語言模型](courses/04-nlp-llm.md) | 31 | Transformer、LLM 訓練、微調與對齊 | Hugging Face LLM Course、CS336 |
| 05 | [生成式 AI 應用開發與提示工程](courses/05-generative-ai-apps.md) | 32 | LLM API、提示工程、RAG | 微軟 Generative AI for Beginners |
| 06 | [AI 代理、MCP 與 AI 輔助程式開發](courses/06-ai-agents.md) | 34 | Agent 設計模式、框架、MCP、程式代理 | 吳恩達 Agentic AI、HF Agents Course |
| 07 | [電腦視覺、擴散模型、多模態與語音](courses/07-vision-multimodal.md) | 23 | CV、影像生成、多模態、語音 AI | CS231n、HF Diffusion Course |
| 08 | [強化學習與機器人學習](courses/08-reinforcement-learning.md) | 23 | RL 理論與實作、機器人 | HF Deep RL Course |
| 09 | [MLOps、LLMOps 與 AI 系統工程](courses/09-mlops-llmops.md) | 30 | 部署、監控、評估、GPU 效能 | Made With ML、LLM Zoomcamp |
| 10 | [AI 安全、倫理與治理](courses/10-ai-safety-ethics.md) | 20 | AI 風險、對齊、倫理、政策 | BlueDot Impact |

### 中文、認證與大學課程

| # | 分類 | 條目數 | 內容 |
|---|---|---|---|
| 11 | [中文原生課程與資源](courses/11-chinese-resources.md) | 79 | 李宏毅、林軒田、李沐；兩岸大學課程與開源教材；Datawhale 教程地圖；中文學習平台 |
| 12 | [AI 證照與認證](courses/12-certifications.md) | 30+ | AWS、Azure、Google Cloud、NVIDIA、Claude、OpenAI、Databricks、治理與資安認證、iPAS、阿里雲、華為 |
| 13 | [大學公開課總覽（依學校）](courses/13-university-courses.md) | 103 | 史丹佛、MIT、柏克萊、CMU、哈佛，以及美、加、歐、亞各校的公開課表 |

### 依身分與目的

| # | 分類 | 條目數 | 內容 |
|---|---|---|---|
| 14 | [垂直領域與專題](courses/14-domain-applications.md) | 64 | 圖機器學習、因果推論、時間序列、推薦系統、邊緣 AI、AI 資安與紅隊、AI for Science、醫療、金融 |
| 15 | [商業、產品與領導者](courses/15-business-leadership.md) | 31 | 免費入門、大學專項課程、商學院高階課程、AI 產品管理 |
| 16 | [教育工作者、K-12 與青少年](courses/16-educators-k12.md) | 28 | 教師 AI 課程、中小學教材、台灣與中國大陸的教育政策與資源 |
| 17 | [無程式碼自動化、Vibe Coding 與創意 AI](courses/17-nocode-creative.md) | 32 | n8n、Dify、Coze、Vibe Coding、影像與影片創作工具 |
| 18 | [先修：程式、資料科學與 CS 基礎](courses/18-prerequisites.md) | 22 | Python、Git、資料科學、完整自學課綱 |

### 延伸資源

| # | 分類 | 條目數 | 內容 |
|---|---|---|---|
| 19 | [免費教科書與書籍](courses/19-books.md) | 48 | 可合法免費閱讀的機器學習、深度學習、LLM、RL 教科書，含中文原創書 |
| 20 | [YouTube 頻道、Podcast、電子報與社群](courses/20-channels-communities.md) | 69 | 持續跟上 AI 發展的資訊來源 |
| 21 | [線上學位、訓練營、暑期學校與研究培訓](courses/21-degrees-bootcamps.md) | 29 | 高性價比線上碩士、梯次課程、暑期學校、研究駐點計畫 |
| 22 | [各國 AI 全民教育計畫與非英語資源](courses/22-global-programs.md) | 29 | 各國政府計畫、企業公益培訓、各語言代表資源 |

> 條目數為各分類表格與詳解的筆數，同一門課可能出現在多個分類（例如同時列於主題頁與大學總覽）。

---

## 分析與指南

| 文件 | 內容 |
|---|---|
| 📊 [全網 AI 課程分析報告](docs/analysis.md) | 2026 年趨勢、平台比較、免費 vs 付費、選課決策框架、常見陷阱、Top 10 精選；含 2026 年 11 月增補 |
| 🧭 [學習平台總覽](docs/platforms.md) | 全球與中文的 60 多個學習平台：費用模式、強項與適合對象 |
| 🗺️ [學習路線圖](docs/learning-paths.md) | 7 條路線（職場應用、應用工程師、代理工程師、ML 扎根、LLM 研究、MLOps、全中文），含里程碑專案 |
| 📖 [中英術語對照表](docs/glossary.md) | 近 100 個 AI 常用術語，含台灣與中國大陸譯名對照 |

---

## 2026 年重點觀察

1. **AI 代理是最熱門主題**：吳恩達、Hugging Face、微軟、Google × Kaggle、柏克萊、史丹佛、Anthropic、OpenAI 都推出代理課程；課程重點正從「串框架」轉向「評估與上下文工程」。
2. **MCP、技能（Skills）與上下文工程成為新必修**：Hugging Face 新推出的 Context Course、微軟 18 課的代理課綱、DeepLearning.AI 與 Anthropic 的短課都已涵蓋。
3. **模型廠商學院快速擴張**：Anthropic Academy 於 2026 年 3 月以 13 門課上線，更名 Claude Academy 後到 11 月約有 28 門；Google DeepMind 與倫敦大學學院推出 8 門課的「AI 研究基礎」；Google AI 專業證書成為 Coursera 上最受歡迎的生成式 AI 證書。
4. **免費模式收緊，但開源資源更豐富**：Coursera 取消免費旁聽、DeepLearning.AI 推出訂閱；同時大學公開課、GitHub 開源課綱與中文開源教程持續增加。
5. **認證體系全面改版**：微軟 AI-900／AI-102／DP-100 退役並推出商務認證；AWS 新增生成式 AI 開發者專業認證；Anthropic 推出 Claude 認證（限合作夥伴）；治理與資安認證（AIGP、SecAI+ 等）興起。
6. **AI 素養政策化**：歐盟《AI 法》要求組織確保 AI 素養；中國大陸發布中小學 AI 通識教育指南；台灣 TAICA 聯盟兩年內擴大到 63 校。

完整內容請見 [分析報告](docs/analysis.md)。

---

## 圖例說明

**程度**

| 標示 | 意義 |
|---|---|
| ⭐ 入門 | 不需或只需少量先備知識 |
| ⭐⭐ 中級 | 需要 Python 程式能力與基礎概念 |
| ⭐⭐⭐ 進階 | 需要扎實的數學、深度學習或系統基礎（多為研究所等級） |

**費用**

| 標示 | 意義 |
|---|---|
| 免費 | 內容完全免費（可能需要註冊帳號） |
| 免費（含證書） | 內容與證書皆免費 |
| 部分免費 | 僅部分內容免費，例如 Coursera 僅首個模組可免費預覽；完整內容或證書需付費 |
| 付費 | 需付費才能學習 |

---

## 倉庫結構

```
ai-courses/
├── README.md                          # 總覽（本頁）
├── CONTRIBUTING.md                    # 貢獻指南與課程條目範本
├── LICENSE                            # CC BY 4.0 授權條款
├── courses/                           # 22 個分類
│   ├── 01-ai-literacy.md              # AI 通識與入門
│   ├── 02-ml-foundations.md           # 機器學習基礎與數學
│   ├── 03-deep-learning.md            # 深度學習
│   ├── 04-nlp-llm.md                  # NLP 與大型語言模型
│   ├── 05-generative-ai-apps.md       # 生成式 AI 應用開發與提示工程
│   ├── 06-ai-agents.md                # AI 代理、MCP 與 AI 輔助程式開發
│   ├── 07-vision-multimodal.md        # 電腦視覺、擴散模型、多模態與語音
│   ├── 08-reinforcement-learning.md   # 強化學習與機器人學習
│   ├── 09-mlops-llmops.md             # MLOps、LLMOps 與 AI 系統工程
│   ├── 10-ai-safety-ethics.md         # AI 安全、倫理與治理
│   ├── 11-chinese-resources.md        # 中文原生課程與資源
│   ├── 12-certifications.md           # AI 證照與認證
│   ├── 13-university-courses.md       # 大學公開課總覽（依學校）
│   ├── 14-domain-applications.md      # 垂直領域與專題
│   ├── 15-business-leadership.md      # 商業、產品與領導者
│   ├── 16-educators-k12.md            # 教育工作者、K-12 與青少年
│   ├── 17-nocode-creative.md          # 無程式碼、Vibe Coding 與創意 AI
│   ├── 18-prerequisites.md            # 先修：程式、資料科學與 CS 基礎
│   ├── 19-books.md                    # 免費教科書與書籍
│   ├── 20-channels-communities.md     # YouTube、Podcast、電子報與社群
│   ├── 21-degrees-bootcamps.md        # 學位、訓練營、暑期學校與研究培訓
│   └── 22-global-programs.md          # 各國計畫與非英語資源
└── docs/
    ├── analysis.md                    # 全網 AI 課程分析報告
    ├── platforms.md                   # 學習平台總覽
    ├── learning-paths.md              # 學習路線圖
    └── glossary.md                    # 中英術語對照表
```

---

## 更新紀錄

| 日期 | 版本 | 內容 |
|---|---|---|
| 2026-11-10 | 第二版修訂 | 加入 CC BY 4.0 授權；README 開頭新增特色說明與英文、簡體中文摘要 |
| 2026-11-10 | 第二版 | 由 12 類擴充為 22 類，條目由約 110 筆增至 850 多筆；新增大學公開課總覽、垂直領域、商業領導者、教育與 K-12、無程式碼與創意 AI、先修基礎、免費教科書、頻道與社群、學位與訓練營、各國計畫，以及學習平台總覽；原 12 類各自新增延伸清單並更新至 2026 年 11 月的資訊；全數 GitHub 連結完成驗證 |
| 2026-10-13 | 初版 | 12 個分類、約 100 門課程與 11 項認證，分析報告、7 條學習路線、術語表 |

---

## 資料說明與免責聲明

- 本倉庫內容根據 2026 年 10–11 月的公開資料整理，來源包括課程官方網站與官方 GitHub 倉庫、大學課程頁面、平台目錄、AI 公司官方學院，以及部分第三方評比與新聞報導（主要來源列於[分析報告](docs/analysis.md#9-主要參考資料)）。
- **課程的價格、時長、證書政策、開課日期與內容經常變動**。標示「以官方為準」「依官網」的資訊多來自二手資料，報名或付費前請務必至官方頁面確認。
- GitHub 倉庫連結已全數驗證；其他網站連結以官方首頁或課程主頁為主，但未能逐一開啟查核，若遇失效歡迎回報。
- 本倉庫與文中提及的任何機構、平台或課程均無合作或贊助關係；點評僅代表整理者觀點。
- 課程名稱、商標與內容之權利屬於各原提供者。

---

## 授權

本倉庫的原創內容（資料整理、中文翻譯、介紹與點評、分析報告與學習路線）以 [創用 CC 姓名標示 4.0 國際（CC BY 4.0）](LICENSE) 授權。

- **你可以**：自由分享、轉載、改寫，包含商業用途
- **條件是**：標示出處（例如「AI 課程大全，AIshihzong/ai-courses」）、附上本倉庫連結與授權條款連結，並說明是否有修改
- **不在授權範圍內**：文中提及的課程名稱、商標、課程內容與第三方網站資料，權利屬於各原提供者

---

## 參與貢獻

歡迎透過 Issue 或 Pull Request：
- 推薦優質課程（特別是中文課程）
- 回報過期資訊或失效連結
- 改進翻譯與點評

詳見 [貢獻指南](CONTRIBUTING.md)。
