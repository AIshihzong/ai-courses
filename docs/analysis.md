# 全網 AI 課程分析報告（2026 年 10 月）

> 本報告根據 2026 年 10 月 13 日進行的網路搜尋與資料整理，分析目前全球主要 AI 課程的版圖、趨勢、平台差異與選課策略。
> 收錄的課程詳見 [`courses/`](../courses/) 目錄的 12 個分類檔案。

[← 回到總覽](../README.md)

---

## 重點摘要

1. **AI 代理（Agent）是 2025–2026 年最熱門的課程主題。** 吳恩達、Hugging Face、微軟、Google × Kaggle、柏克萊大學、Anthropic、OpenAI 都推出了 Agent 課程；Google 與 Kaggle 在 2025 年 11 月舉辦的 5 天代理密集課吸引超過 150 萬名學習者。
2. **MCP 與「上下文工程」成為新的必修內容。** 模型上下文協定（MCP）已有 Hugging Face、微軟、Anthropic、DeepLearning.AI 等多門專門課程。
3. **模型廠商自辦學院成為主流管道。** Anthropic Academy、OpenAI Academy、Google Skills（2025 年 10 月整合推出，近 3,000 門課程）、NVIDIA DLI、微軟 Learn 與 AWS Skill Builder 都提供大量免費課程——品質高、更新快，但難免以自家產品為中心。
4. **「從零打造 LLM」的課程熱潮。** 史丹佛 CS336、Karpathy 的 Zero to Hero 與 nanochat、Raschka 的《LLMs from Scratch》、Datawhale 的 Happy-LLM，都在回應「不只會呼叫 API，還要懂原理」的需求。
5. **免費模式正在收緊。** Coursera 自 2025 年中起以「預覽」（通常僅首個模組免費）取代過去的免費旁聽；DeepLearning.AI 推出 Pro 訂閱制。相對地，GitHub 開源課綱、Hugging Face 課程與大學公開課仍完全免費。
6. **AI 認證體系大改版。** 微軟 AI-900／AI-102 於 2026 年 6 月退役並由 AI-901／AI-103 取代；AWS 機器學習專業認證退役，新增生成式 AI 開發者專業認證。
7. **中文資源已相當成熟。** 李宏毅的生成式 AI 系列、李沐的《動手學深度學習》，以及 Datawhale 的 Hello-Agents（GitHub 約 6.5 萬星）等，讓中文學習者可以用母語完成從入門到進階的學習。
8. **知識幾乎都是免費的，真正稀缺的是實作與回饋。** 付費的價值主要在評分回饋、證書、學習結構與社群，而非內容本身。

---

## 1. 研究範圍與方法

**搜尋範圍**：
- 平台目錄：Coursera、edX、DeepLearning.AI、Hugging Face Learn、Kaggle Learn、微軟 GitHub 課綱、DataTalksClub、Udemy、Udacity
- 原廠學院：Anthropic、OpenAI、Google（Google Skills）、NVIDIA DLI、AWS、微軟
- 大學公開課：史丹佛（CS229、CS224N、CS231n、CS336、CS25 等）、MIT、哈佛、柏克萊、CMU、紐約大學、台大
- 評比與整理：Class Central、KDnuggets 及多份 2026 年課程推薦清單
- 中文資源：台灣大學公開課、Datawhale、台灣政府學習平台與媒體整理

**篩選標準**：
1. **權威性**：由頂尖大學、知名研究者或第一方廠商製作
2. **時效性**：內容是否反映 2024 年後的技術發展（LLM、Agent、MCP 等）；經典但較舊的課程會標註其限制
3. **可取得性**：優先收錄免費或可部分免費取得的課程
4. **實作比重**：是否包含程式作業、專案或可執行的 Notebook
5. **社群評價**：學習者數量、GitHub 星數、評比中的推薦頻率

**研究限制**：
- 許多 2026 年的「最佳課程」清單帶有聯盟行銷或自家課程推廣性質，本報告僅將其作為線索，盡量回到官方來源核對。
- 部分資訊（如課程數量、價格、日期）只能取得二手資料，已在各課程說明中註明「以官方為準」。
- AI 課程變動極快，本報告反映的是 2026 年 10 月的狀態。

---

## 2. 2026 年 AI 課程版圖：九大趨勢

### 趨勢 1：從「學模型」轉向「建代理」

2023 年的熱門關鍵字是「提示工程」，2024 年是「RAG」，2025–2026 年則是「**代理式 AI（Agentic AI）**」。代表性課程：

| 課程 | 提供者 | 特色 |
|---|---|---|
| Agentic AI | DeepLearning.AI（吳恩達） | 四大設計模式：反思、工具使用、規劃、多代理；重視評估 |
| AI Agents Course | Hugging Face | 免費、多框架（smolagents、LlamaIndex、LangGraph）、有排行榜 |
| AI Agents for Beginners | 微軟 | 18 課開源課綱，涵蓋上下文工程、MCP、電腦操作代理 |
| 5-Day AI Agents Intensive | Google × Kaggle | 150 萬+ 學習者，白皮書品質高 |
| Agentic AI MOOC | 柏克萊大學 | 連續三期，研究前沿 |

**觀察**：課程重點正從「如何串接框架」轉向「**如何評估與除錯代理**」——吳恩達的課程用整個模組講評估與錯誤分析，這反映了業界在實際部署代理時遇到的最大痛點。

### 趨勢 2：MCP 與上下文工程成為新必修

MCP 從 Anthropic 於 2024 年底提出的協定，迅速成為代理連接外部工具與資料的事實標準。2026 年已有 Hugging Face MCP Course、微軟 MCP for Beginners（支援 6 種程式語言）、Anthropic 的 MCP 入門與進階課程，以及 DeepLearning.AI 的 MCP 短課。「上下文工程（Context Engineering）」與「代理技能（Agent Skills）」也開始出現在課綱中。

### 趨勢 3：模型廠商自辦學院崛起

| 學院 | 特色 | 注意事項 |
|---|---|---|
| Anthropic Academy | 免費、含證書；涵蓋 AI 流暢力、Claude API、Claude Code、MCP | 課程隨產品改版汰換 |
| OpenAI Academy | 免費；AI 基礎、應用 AI、代理與工作流程 | 結業證明 ≠ 正式認證 |
| Google Skills | 2025 年 10 月整合推出，近 3,000 門課程 | 部分實驗室與證照需訂閱 |
| NVIDIA DLI | 部分免費自學課；偏部署與加速 | 進階課程與認證付費 |
| 微軟（GitHub 課綱 + Learn） | 完全免費、開源、多語翻譯 | 範例偏 Azure 生態系 |

**觀察**：第一方課程的優勢是與產品同步、免費且品質穩定；缺點是視角偏向自家產品。建議**以中立課程建立觀念，再用原廠課程學工具**。

### 趨勢 4：「從零打造」的課程熱潮

越來越多學習者希望真正理解 LLM，而非只會呼叫 API：

| 資源 | 難度 | 形式 |
|---|---|---|
| Karpathy《Neural Networks: Zero to Hero》 | ⭐⭐～⭐⭐⭐ | 影片 + 程式 |
| Raschka《Build a LLM (From Scratch)》 | ⭐⭐ | 書籍 + 免費程式碼 |
| Datawhale《Happy-LLM》 | ⭐⭐ | 中文開源教程 |
| Karpathy nanochat | ⭐⭐⭐ | 約 8,000 行完整類 ChatGPT 流程 |
| 史丹佛 CS336 | ⭐⭐⭐ | 研究所課程，從分詞到 RL 後訓練 |

### 趨勢 5：頂尖大學課程持續開放

史丹佛 CS336（2026 春季錄影自 4 月起公開）、CS224N（2026 冬季）、CS231n、MIT 6.S191（2026 年 1 月）等課程持續公開教材與錄影。CME296（擴散與大型視覺模型）據報導也在 2026 年免費公開教材。**全球最好的 AI 教育，絕大部分是免費的。**

### 趨勢 6：AI 輔助程式開發課程爆發

隨著 Claude Code、Cursor、Gemini CLI 等程式代理普及，出現大量相關課程：Anthropic 的 Claude Code in Action、DataTalksClub 的 AI Dev Tools Zoomcamp（2026 年 8 月 31 日開課）、Kaggle 2026 年 6 月的 Vibe Coding 密集課，以及 Udemy 上大量付費課程。

### 趨勢 7：強化學習因推理模型重新受到重視

GRPO、可驗證獎勵的強化學習（RLVR）等 LLM 後訓練技術，讓 RL 重新成為熱門技能。Hugging Face LLM Course 新增推理模型章節，CS336 也將 RL 後訓練納入作業。

### 趨勢 8：免費模式收緊、訂閱制興起

| 平台 | 變化 |
|---|---|
| Coursera | 2025 年中起以「預覽」取代「旁聽」，通常僅首個模組免費；仍可申請助學金 |
| DeepLearning.AI | 推出 Pro 會員，評分作業與證書需訂閱（官網標示年繳約每月 25 美元） |
| Google Skills | 基礎課程免費，進階實驗室與證照需訂閱 |

**對學習者的影響**：「先在 Coursera 免費旁聽吳恩達的課」這個過去最常見的建議已不再完全適用。替代方案：
- 申請 Coursera 助學金（Financial Aid）
- 改用完全免費的替代課程（見下表）

| 付費／部分免費課程 | 完全免費的替代選擇 |
|---|---|
| 吳恩達 Machine Learning Specialization | Google MLCC + Kaggle Learn + CS229 錄影 |
| 吳恩達 Deep Learning Specialization | fast.ai + MIT 6.S191 + 《動手學深度學習》 |
| Generative AI with LLMs | Hugging Face LLM Course |
| 阿爾伯塔 RL 專項 | Hugging Face Deep RL Course + David Silver 講座 + Sutton & Barto |
| Coursera 數學專項 | 3Blue1Brown + MIT 18.06 + 《Mathematics for ML》免費電子書 |

### 趨勢 9：AI 認證大改版

- 微軟：AI-900 → AI-901；AI-102 → AI-103（Azure AI Apps and Agents Developer Associate），2026 年 6 月 30 日生效
- AWS：ML Specialty 退役（2026 年 3 月 31 日）；新增 Generative AI Developer – Professional；ML Engineer Associate 改版中
- Google Cloud：Generative AI Leader（非技術導向）
- OpenAI：正式認證仍為邀請制試行
- 台灣：iPAS AI 應用規劃師報考人數大增

**觀察**：所有改版的共同方向是**加入生成式 AI 與代理式 AI**，淘汰以傳統機器學習為主的考試。詳見 [12｜認證](../courses/12-certifications.md)。

---

## 3. 主要學習平台比較

| 平台 | 費用模式 | 證書 | 優勢 | 劣勢 | 最適合 |
|---|---|---|---|---|---|
| **Coursera** | 預覽免費，訂閱或單門付費 | 付費，含大學與企業專業證書 | 結構完整、證書認可度高 | 免費範圍已大幅縮小 | 需要正式證書者 |
| **edX** | 部分課程可免費旁聽，證書付費 | 付費 | 哈佛、MIT 等名校課程 | 部分課程旁聽有時限 | 名校課程愛好者 |
| **DeepLearning.AI** | 短課影片免費；Pro 訂閱 | Pro 會員 | 更新最快、吳恩達品牌、與業界合作 | 短課較零散 | 想追新技術的開發者 |
| **Hugging Face Learn** | 完全免費 | 多數免費 | 開源生態系實作、社群活躍 | 需一定程式基礎 | 想用開源模型的工程師 |
| **微軟 GitHub 課綱** | 完全免費開源 | 無 | 課綱完整、多語翻譯（含中文） | 偏 Azure 生態系 | 自學者、教師 |
| **大學公開課**（YouTube/OCW） | 完全免費 | 無 | 世界頂尖的深度與嚴謹度 | 無評分、無助教、需高度自律 | 想打深厚基礎、走研究者 |
| **原廠學院** | 多數免費 | 多數免費 | 第一方、與產品同步 | 偏向自家產品 | 使用該廠商工具的人 |
| **Kaggle Learn** | 完全免費 | 免費 | 瀏覽器即可實作、可接競賽 | 深度有限 | 初學者動手練習 |
| **DataTalksClub** | 完全免費 | 完成專案免費 | 社群梯次制、專案導向 | 直播時程固定 | 想要同儕與期限督促者 |
| **Udemy** | 單門付費（常有折扣） | 付費完課證明 | 選擇多、跟進新工具快 | 品質參差、行銷文多 | 想學特定工具的人 |
| **Udacity** | 訂閱付費 | 奈米學位 | 專案審閱與導師回饋 | 價格高 | 需要人工回饋的轉職者 |
| **中文平台**（YouTube／B 站／政府平台） | 多數免費 | 政府平台多有完課證明 | 母語學習 | 前沿資訊較英文晚 | 中文學習者入門 |

---

## 4. 各主題資源成熟度

| 主題 | 資源豐富度 | 免費資源品質 | 更新速度 | 首推入門課 |
|---|---|---|---|---|
| AI 通識 | ★★★★★ | ★★★★★ | 中 | Elements of AI |
| 機器學習基礎 | ★★★★★ | ★★★★★ | 慢（內容穩定） | Google MLCC / 吳恩達 ML 專項 |
| 深度學習 | ★★★★★ | ★★★★★ | 中 | fast.ai / Karpathy Zero to Hero |
| NLP 與 LLM | ★★★★★ | ★★★★★ | 快 | Hugging Face LLM Course |
| 生成式 AI 應用 | ★★★★★ | ★★★★☆ | 非常快 | 微軟 Generative AI for Beginners |
| AI 代理與 MCP | ★★★★☆ | ★★★★☆ | 非常快 | 吳恩達 Agentic AI / HF Agents Course |
| 電腦視覺與多模態 | ★★★★☆ | ★★★★☆ | 中 | CS231n |
| 強化學習 | ★★★☆☆ | ★★★★☆ | 慢（LLM 後訓練方向較快） | HF Deep RL Course |
| MLOps／LLMOps | ★★★☆☆ | ★★★★☆ | 中 | Made With ML / LLM Zoomcamp |
| AI 安全與倫理 | ★★★☆☆ | ★★★★☆ | 中 | BlueDot Impact |
| 中文資源 | ★★★★☆ | ★★★★★ | 中 | 李宏毅系列 |

**觀察**：
- **代理與 MCP** 課程雖多，但普遍較新、尚未經過時間考驗，且框架變動快；建議重視原理（設計模式、評估），不要過度投資特定框架。
- **MLOps／LLMOps** 與 **評估（Evals）** 是相對缺乏系統化課程的領域，也正是業界最缺的能力。
- **強化學習** 的經典課程大多成形於 2015–2023 年，與 LLM 後訓練的連結需要自行補足。

---

## 5. 免費 vs. 付費：什麼值得花錢？

**免費已經足夠的部分**：幾乎所有**知識內容**——頂尖大學的講座、經典教科書、開源課綱、官方文件。

**付費能買到的東西**：

| 付費項目 | 價值 | 何時值得 |
|---|---|---|
| 作業評分與回饋 | 高 | 自學常卡關、缺乏回饋時 |
| 證書 | 中（依證書種類） | 求職、公司報帳、原廠合作要求 |
| 學習結構與期限 | 中～高 | 自律不足、需要外部督促時 |
| 導師與社群 | 高 | 轉職、需要職涯指導時 |
| GPU 算力 | 中 | 需要訓練較大模型時（也可用 Colab、Kaggle 免費額度） |

**建議**：先用免費資源學到「知道自己卡在哪裡」，再針對性地付費；不要一開始就買昂貴的套裝課程。

---

## 6. 選課決策框架

```
第 1 步：確定目標
  ├─ 想「用」AI 提升工作效率          → 01 通識 + 05 應用（無程式）
  ├─ 想「做」AI 應用（開發者）          → 05 應用 → 06 代理 → 09 LLMOps
  ├─ 想「懂」AI 原理（工程師／研究者）  → 02 基礎 → 03 深度學習 → 04 LLM
  └─ 想「管」AI（主管／政策）           → 01 通識 + 10 安全與治理

第 2 步：評估背景
  ├─ 不會寫程式   → 從 01 開始；若要轉技術職，先學 Python
  ├─ 會寫程式     → 可直接從 05 開始，邊做邊補 02–04
  └─ 有 ML 基礎   → 直接進 04、06

第 3 步：評估時間
  ├─ 每週 < 3 小時  → 短課（DeepLearning.AI 短課、Google Skills、Kaggle Learn）
  ├─ 每週 5–10 小時 → 專項課程、Hugging Face 課程、GitHub 課綱
  └─ 每週 > 15 小時 → 大學課程（含作業）、Zoomcamp 梯次

第 4 步：選擇學習風格
  ├─ 先做再懂（由上而下） → fast.ai、Hugging Face、Kaggle
  └─ 先懂再做（由下而上） → 吳恩達系列、大學課程、Karpathy
```

具體路線請見 [學習路線圖](learning-paths.md)。

---

## 7. 常見陷阱

1. **收藏不學**：把幾十門課加入書籤，卻沒有完成任何一門。建議**同時只上一門主課**。
2. **只看不做**：看完影片覺得懂了，實際寫程式卻寸步難行。每門課都要完成作業，並做一個自己的延伸專案。
3. **追逐框架而忽略原理**：代理框架每幾個月就變一次，但反思、工具使用、規劃、評估等原理不會。
4. **跳過基礎**：直接學 LLM 應用沒問題，但遇到效能、成本、可靠性問題時，缺乏基礎會讓你難以除錯。
5. **迷信證書**：證書是起點而非終點，作品集才是求職時最有力的證明。
6. **全盤相信「最佳課程」排行榜**：許多排行榜帶有聯盟行銷性質，請回到官方頁面確認課程內容與更新日期。
7. **學了過時的內容而不自知**：注意課程的錄製年份。2023 年以前的 NLP 課程可能完全沒有 LLM 內容；2024 年以前的應用課程可能沒有代理與 MCP。

---

## 8. 綜合精選 Top 10

若只能挑 10 項資源，本倉庫的建議如下（兼顧不同背景與目標）：

| # | 課程 | 理由 | 分類 |
|---|---|---|---|
| 1 | Elements of AI | 最好的零基礎 AI 通識，免費含證書 | [01](../courses/01-ai-literacy.md) |
| 2 | 李宏毅 生成式 AI 系列 | 中文學習者的首選，從入門到前沿 | [11](../courses/11-chinese-resources.md) |
| 3 | 吳恩達 Machine Learning Specialization | 全球最友善的機器學習入門 | [02](../courses/02-ml-foundations.md) |
| 4 | Karpathy Neural Networks: Zero to Hero | 理解神經網路與 LLM 的最佳影片 | [03](../courses/03-deep-learning.md) |
| 5 | Hugging Face LLM Course | 開源 LLM 實作的官方教材 | [04](../courses/04-nlp-llm.md) |
| 6 | 微軟 Generative AI for Beginners | LLM 應用開發的完整地圖，含中文翻譯 | [05](../courses/05-generative-ai-apps.md) |
| 7 | 吳恩達 Agentic AI | 代理設計模式與評估方法論 | [06](../courses/06-ai-agents.md) |
| 8 | Hugging Face AI Agents Course | 免費、多框架、實作導向的代理課 | [06](../courses/06-ai-agents.md) |
| 9 | 史丹佛 CS336 | 想進入模型訓練領域的試金石 | [04](../courses/04-nlp-llm.md) |
| 10 | LLM Zoomcamp | 把 RAG 系統做到可上線、可評估 | [09](../courses/09-mlops-llmops.md) |

---

## 9. 主要參考資料

以下為本次整理過程中參考的主要網頁（部分為第三方整理，資訊以各課程官方頁面為準）：

**平台與課程官方資訊**
- [DeepLearning.AI – Agentic AI 課程](https://www.deeplearning.ai/courses/agentic-ai/)
- [DeepLearning.AI – Deep Learning Specialization（Pro 會員說明）](https://www.deeplearning.ai/specializations/deep-learning)
- [DeepLearning.AI – Pro 會員公告](https://www.deeplearning.ai/the-batch/announcing-the-deeplearning-ai-pro-membership)
- [DeepLearning.AI 社群公告（2026 年短課）](https://community.deeplearning.ai/c/news-and-announcements/24)
- [Coursera – 新的課程預覽機制](https://blog.coursera.org/introducing-courseras-new-course-preview-experience)
- [Class Central – Coursera 免費修課指南](https://www.classcentral.com/report/coursera-signup-for-free/)
- [Hugging Face Learn](https://huggingface.co/learn)
- [Hugging Face Agents Course（GitHub）](https://github.com/huggingface/agents-course)
- [Claude Academy 課程列表](https://academy.claude.com/courses)
- [微軟 AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners)
- [微軟 MCP for Beginners](https://github.com/microsoft/mcp-for-beginners)
- [微軟 AI for Beginners](https://github.com/microsoft/ai-for-beginners)
- [Google 部落格 – Kaggle AI 代理密集課回顧](https://blog.google/technology/developers/ai-agents-intensive-recap/)
- [Google 部落格 – 機器學習速成班改版](https://blog.google/innovation-and-ai/technology/developers-tools/machine-learning-crash-course/)
- [MIT 6.S191 Introduction to Deep Learning](https://introtodeeplearning.com/)
- [柏克萊 RDI – Agentic AI MOOC（2025 秋）](https://rdi.berkeley.edu/agentic-ai/f25)
- [BlueDot Impact](https://bluedot.org)
- [AWS – AI 認證組合擴充公告](https://aws.amazon.com/blogs/training-and-certification/big-news-aws-expands-ai-certification-portfolio-and-updates-security-certification/)
- [NVIDIA AI Learning Essentials](https://www.nvidia.com/en-us/learn/ai-learning-essentials/)
- [李宏毅 – Introduction to GenAI and ML 2025 Fall](https://speech.ee.ntu.edu.tw/~hylee/GenAI-ML/2025-fall.php)
- [李宏毅 – 生成式人工智慧導論 2024](https://speech.ee.ntu.edu.tw/~hylee/genai/2024-spring.php)
- [台大開放式課程 – 機器學習基石](https://ocw.aca.ntu.edu.tw/courses/mooc0032)
- [Datawhale GitHub](https://github.com/datawhalechina)
- [赫爾辛基大學 – Elements of AI 百萬學習者公告](https://www.helsinki.fi/en/news/artificial-intelligence/elements-ai-has-introduced-one-million-people-basics-artificial-intelligence)

**評比、整理與新聞報導**
- [KDnuggets – Kaggle × Google 5 天代理式 AI 課程](https://www.kdnuggets.com/kaggle-googles-free-5-day-agentic-ai-course)
- [KDnuggets – Hugging Face 5 門免費課程](https://www.kdnuggets.com/5-free-ai-courses-from-hugging-face)
- [KDnuggets – 5 個免費 Zoomcamp](https://kdnuggets.com/5-free-zoomcamps-from-data-pipelines-to-ai-agents)
- [Class Central – AI 代理課程](https://www.classcentral.com/subject/ai-agents)
- [i-programmer – 史丹佛 CME296](https://www.i-programmer.info/news/150-training-a-education/18939-stanfords-cme296-diffusion-a-large-vision-models.html)
- [i-programmer – MIT 深度學習導論](https://www.i-programmer.info/news/150-training-a-education/18878-massachusetts-institute-of-technology-introduction-to-deep-learning.html)
- [Social Media Today – Google Skills 推出](https://www.socialmediatoday.com/news/google-launches-google-skills-tech-training-ai-learning-hub/803412/)
- [How to AI – 微軟 Azure AI 認證 2026](https://howtoai.com/microsoft-ai-certifications/)
- [How to AI – AWS AI 認證 2026](https://howtoai.com/aws-ai-certifications/)
- [數位時代 – 政府免費 AI 課程平台比較](https://www.bnext.com.tw/article/91517/free-government-ai-course-platforms-comparison-guide)
- [StockFeel 股感 – 2026 免費 AI 課程推薦](https://www.stockfeel.com.tw/ai-%E8%AA%B2%E7%A8%8B-%E5%85%8D%E8%B2%BB/)
