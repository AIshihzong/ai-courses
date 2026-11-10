# 06｜AI 代理（Agent）、MCP 與 AI 輔助程式開發

> 適合對象：已會呼叫 LLM API，想打造能「自主規劃、使用工具、完成多步驟任務」的 AI 系統的開發者。
> 這是 2025–2026 年**成長最快**的課程類別。吳恩達、Hugging Face、微軟、Google、柏克萊大學、Anthropic、OpenAI 都推出了 Agent 相關課程；模型上下文協定（Model Context Protocol, MCP）也從新概念變成必修內容。另一個新興分支是「**AI 程式開發代理**」（Coding Agents，如 Claude Code、Cursor 等）的課程。

[← 回到總覽](../README.md)

## 速覽

| # | 課程（中文譯名／英文原名） | 提供者 | 程度 | 費用 | 重點 |
|---|---|---|---|---|---|
| 1 | 代理式 AI / Agentic AI | DeepLearning.AI（吳恩達） | ⭐⭐ | 影片免費，評分與證書需 Pro | 四大代理設計模式 |
| 2 | Hugging Face AI 代理課程 / AI Agents Course | Hugging Face | ⭐～⭐⭐ | 免費（含證書） | 多框架實作 + 排行榜 |
| 3 | 給初學者的 AI 代理 / AI Agents for Beginners | 微軟 | ⭐～⭐⭐ | 免費（GitHub） | 18 課完整課綱 |
| 4 | 5 天 AI 代理密集課 / 5-Day AI Agents Intensive | Google × Kaggle | ⭐⭐ | 免費 | 白皮書 + 實作 |
| 5 | 柏克萊代理式 AI 系列 MOOC / Agentic AI & LLM Agents MOOC | 加州大學柏克萊分校 | ⭐⭐～⭐⭐⭐ | 免費 | 前沿講座 |
| 6 | Hugging Face MCP 課程 / MCP Course | Hugging Face | ⭐⭐ | 免費（含證書） | MCP 從基礎到實戰 |
| 7 | 給初學者的 MCP / MCP for Beginners | 微軟 | ⭐～⭐⭐ | 免費（GitHub） | 多語言 MCP 範例 |
| 8 | Anthropic MCP 與 Claude Code 課程 | Anthropic | ⭐⭐ | 免費（含證書） | 第一方 MCP／程式代理 |
| 9 | LangChain 學院 / LangChain Academy | LangChain | ⭐⭐ | 免費 | LangGraph 代理 |
| 10 | DeepLearning.AI 代理主題短課 | DeepLearning.AI 與合作夥伴 | ⭐⭐ | 免費觀看 | 框架與工具專題 |
| 11 | AI 開發工具 Zoomcamp / AI Dev Tools Zoomcamp | DataTalksClub | ⭐⭐ | 免費 | AI 輔助軟體開發 |
| 12 | 代理式 AI 奈米學位 / Agentic AI Nanodegree | Udacity | ⭐⭐～⭐⭐⭐ | 付費 | 職涯導向專案 |

---

## 1. 代理式 AI（Agentic AI）

- **提供者**：DeepLearning.AI，吳恩達主講
- **程度**：⭐⭐ 中級｜**費用**：DeepLearning.AI 平台可免費旁聽（影片、論壇）；評分作業與證書需 DeepLearning.AI Pro 會員｜**時長**：5 個模組，約 8–10 小時（各平台標示略有差異）
- **連結**：<https://www.deeplearning.ai/courses/agentic-ai/>（亦於 Coursera 開設）

**簡介**：吳恩達親自主講的代理式 AI 課程，圍繞他提出的**四大代理設計模式**，並強調「評估與錯誤分析」是打造可靠代理的關鍵。

**課程結構**：
1. 代理式工作流程簡介：何時需要代理、自主程度的光譜
2. **反思（Reflection）**：讓模型檢查並改進自己的輸出
3. **工具使用（Tool Use）**：連接資料庫、API、網路搜尋、程式執行
4. 評估與錯誤分析：建立評估指標、分析失敗案例、迭代改進
5. **規劃（Planning）** 與 **多代理協作（Multi-agent）**：LLM 規劃與執行、線性管線、主管-工作者階層、全互連等溝通模式

**實作範例**：研究代理、客服代理、市場研究團隊等。

**點評**：重視概念與工程方法，而非綁定特定框架，學到的技能可遷移到任何工具。是 2026 年最受推薦的代理入門課之一。

---

## 2. Hugging Face AI 代理課程（AI Agents Course）

- **提供者**：Hugging Face
- **程度**：⭐ 入門～⭐⭐ 中級｜**費用**：免費，完成可取得證書｜**時長**：約 4 個主要單元，每單元約一週（每週 3–4 小時），無截止期限
- **連結**：<https://huggingface.co/learn/agents-course>

**課程結構**：
- 單元 1：代理基礎（思考-行動-觀察循環、工具、LLM 角色）
- 單元 2：代理框架——**smolagents、LlamaIndex、LangGraph**
- 單元 3：代理式 RAG 應用案例
- 單元 4：期末專案——打造代理挑戰基準測試，並登上公開排行榜
- 加分單元：為函式呼叫微調模型、可觀測性與評估、在遊戲（寶可夢）中使用代理

**點評**：免費、實作導向，且讓你比較多種主流框架，是最受歡迎的免費代理課程之一。

---

## 3. 給初學者的 AI 代理（AI Agents for Beginners）

- **提供者**：微軟
- **程度**：⭐～⭐⭐｜**費用**：免費開源｜**時長**：18 課（依 GitHub 倉庫標題）
- **連結**：<https://github.com/microsoft/ai-agents-for-beginners>

**18 課主題**（依官方課表）：代理簡介與應用案例、代理框架探索、代理設計模式、工具使用、代理式 RAG、建立可信任的代理、規劃、多代理、後設認知（Metacognition）、代理上線、代理協定（MCP、A2A、NLWeb）、上下文工程（Context Engineering）、代理記憶管理、Microsoft Agent Framework、電腦操作代理（CUA）、部署可擴展的代理、建立本機 AI 代理、代理安全。

**點評**：課程持續擴充（早期版本為 12 課），每課附影片與程式範例，並提供包含中文在內的多國語言翻譯。建議先完成同系列的 *Generative AI for Beginners*。

---

## 4. 5 天 AI 代理密集課（5-Day AI Agents Intensive Course with Google）

- **提供者**：Google × Kaggle
- **程度**：⭐⭐ 中級｜**費用**：免費（需 Kaggle 帳號與 Google AI Studio API 金鑰）｜**時長**：5 天，每天約 1–2 小時
- **連結**：Google 官方介紹 <https://blog.google/technology/developers/ai-agents-intensive-recap/>；課程本體位於 Kaggle 學習指南（<https://www.kaggle.com/learn>，搜尋 "5-Day AI Agents"）

**簡介**：2025 年 11 月舉辦的直播課程，吸引超過 150 萬名學習者，之後轉為可自訂進度的 Kaggle 學習指南。每天包含一份白皮書、一集 45–60 分鐘的 Podcast 與實作程式實驗室（Codelab）。2026 年 6 月 15–19 日另推出以 **Vibe Coding** 為主題的新一期，同樣已轉為自學版本。

**主題**：
- 2025 年版：代理架構與「何時真的需要代理」、工具與 MCP、上下文工程與記憶、代理評估與品質、多代理系統與上線（使用 Google Agent Development Kit, ADK）
- 2026 年版：代理工具與 MCP、可攜式「代理技能（Agent Skills）」、安全與評估框架、生產環境部署

**點評**：白皮書品質高，適合想在短時間內掌握代理全景的工程師。結業專題與雲端部署為選修，可能需要啟用計費的 Google Cloud 帳號。

---

## 5. 柏克萊代理式 AI 系列 MOOC（UC Berkeley Agentic AI / LLM Agents MOOC）

- **提供者**：加州大學柏克萊分校 RDI 中心，Dawn Song（宋曉冬）教授
- **程度**：⭐⭐～⭐⭐⭐｜**費用**：免費
- **連結**：
  - 2025 秋季「代理式 AI」：<https://rdi.berkeley.edu/agentic-ai/f25>
  - 2025 春季「進階 LLM 代理」：<https://rdi.berkeley.edu/adv-llm-agents/sp25>
  - 2024 秋季「LLM 代理」：<https://rdi.berkeley.edu/llm-agents/f24>

**簡介**：連續三期的公開 MOOC，邀請 OpenAI、Google DeepMind、NVIDIA、微軟等機構的研究者主講。2025 秋季版約 12 堂講座，主題涵蓋 LLM 基礎、推理與規劃、代理框架與基礎設施、代理評估、多代理系統、AI 安全與資安，以及代表性應用。

**點評**：研究深度高，最適合想了解「代理技術前沿與開放問題」的人。過去梯次曾搭配結業證書與 AgentX 黑客松，實際規定依各期公告為準。

---

## 6. Hugging Face MCP 課程（Model Context Protocol Course）

- **提供者**：Hugging Face（與 Anthropic 合作）
- **程度**：⭐⭐ 中級｜**費用**：免費，可取得證書
- **連結**：<https://huggingface.co/learn/mcp-course>

**簡介**：從 MCP 的基本概念（主機、客戶端、伺服器、工具、資源、提示）到建立端到端的 MCP 應用，並結合 Hugging Face 生態系實作。

**點評**：學習 MCP 的優質免費入門，內容實作導向。

---

## 7. 給初學者的 MCP（MCP for Beginners）

- **提供者**：微軟
- **程度**：⭐～⭐⭐｜**費用**：免費開源
- **連結**：<https://github.com/microsoft/mcp-for-beginners>

**簡介**：以 .NET、Java、TypeScript、JavaScript、Rust 與 Python 等多種語言示範 MCP，課綱分為多個核心模組（00–11），涵蓋核心概念、安全性、建立第一個伺服器與客戶端、進階主題與實務案例，並隨 MCP 規格更新。

**點評**：多語言範例是最大特色，適合非 Python 技術棧的開發團隊。

---

## 8. Anthropic MCP 與 Claude Code 課程

- **提供者**：Anthropic（Anthropic Academy／Claude Academy）
- **程度**：⭐⭐ 中級｜**費用**：免費，可取得證書
- **連結**：<https://academy.claude.com/courses>

| 課程 | 內容 |
|---|---|
| Claude Code 實戰（Claude Code in Action） | AI 程式助理的架構、上下文管理、自訂指令、在 Claude Code 中整合 MCP 伺服器、GitHub 工作流程自動化、Hooks 與 SDK |
| Claude Code 101 | 給第一次接觸程式代理的開發者，約 1.5 小時 |
| MCP 入門（Introduction to Model Context Protocol） | 以 Python 從零建立 MCP 伺服器與客戶端 |
| MCP 進階主題（Model Context Protocol: Advanced Topics） | MCP 入門的進階續篇 |

**延伸**：DeepLearning.AI 與 Anthropic 合作的短課，如「MCP：打造豐富上下文的 AI 應用（MCP: Build Rich-Context AI Apps with Anthropic）」與 2026 年 2 月推出的「代理技能（Agent Skills with Anthropic）」。

**點評**：MCP 由 Anthropic 提出，第一方課程能最快反映規格變化。Claude Code in Action 對想把 AI 程式代理導入日常開發流程的團隊特別實用。

---

## 9. LangChain 學院（LangChain Academy）

- **提供者**：LangChain
- **程度**：⭐⭐ 中級｜**費用**：免費
- **連結**：<https://academy.langchain.com/>

**簡介**：以 **LangGraph** 為核心的代理開發課程，涵蓋狀態圖、記憶、人機協作（Human-in-the-loop）、多代理與部署。

**點評**：若團隊已決定使用 LangChain/LangGraph 生態系，官方學院是最直接的學習資源。

---

## 10. DeepLearning.AI 代理主題短課

- **提供者**：DeepLearning.AI 與各家合作夥伴
- **程度**：⭐⭐｜**費用**：影片可免費觀看｜**時長**：每門約 1–2 小時
- **連結**：<https://www.deeplearning.ai/short-courses/>

**代表性短課（範例）**：
- 以 LangGraph 打造 AI 代理（AI Agents in LangGraph）
- 以 crewAI 打造多代理系統（Multi AI Agent Systems with crewAI）
- 以 Google ADK 打造即時語音代理（Building Live Voice Agents with Google's ADK，2026 年 1 月）
- 文件 AI：從 OCR 到代理式文件擷取（Document AI: From OCR to Agentic Doc Extraction，2026 年 1 月）
- Gemini CLI：以開源代理寫程式與創作（Gemini CLI: Code & Create with an Open-Source Agent，2026 年 2 月）

**點評**：短課是「學一個新框架」最快的方式，但缺乏系統性；建議先上完第 1–3 項任一門完整課程再挑選短課補強。

---

## 11. AI 開發工具 Zoomcamp（AI Dev Tools Zoomcamp）

- **提供者**：DataTalksClub（Alexey Grigorev）
- **程度**：⭐⭐ 中級｜**費用**：免費（含證書，需完成專案）
- **連結**：<https://github.com/DataTalksClub/ai-dev-tools-zoomcamp>

**簡介**：專注於「用 AI 工具開發軟體」的社群課程。2026 年梯次於 8 月 31 日開課，共五個模組：AI 原生開發工作流程 → 建置並交付 AI 輔助的全端應用 → 測試、容器化與部署 → DevOps 與可觀測性 → 程式代理的積木（可重用的技能與專門化子代理）。

**點評**：社群活躍、專案導向，適合想系統化掌握 AI 程式開發代理的工程師。錯過直播梯次仍可自學。

---

## 12. 代理式 AI 奈米學位（Agentic AI Nanodegree）

- **提供者**：Udacity
- **程度**：⭐⭐～⭐⭐⭐｜**費用**：付費訂閱
- **連結**：<https://www.udacity.com/>（搜尋 "Agentic AI"）

**點評**：多份評比將其評為最嚴謹、職涯導向的付費代理課程，提供專案審閱與導師回饋。若需要有人批改專案與督促進度，可考慮；否則免費資源已相當完整。

---

## 本類別選課建議

| 你的情況 | 建議路線 |
|---|---|
| 第一次接觸代理 | 吳恩達 Agentic AI（觀念）→ Hugging Face Agents Course（實作） |
| 想用微軟／Azure 技術棧 | Generative AI for Beginners → AI Agents for Beginners → MCP for Beginners |
| 想用 Google 技術棧 | Kaggle 5 天密集課（ADK）→ Google Skills 進階路徑 |
| 想學 MCP | Anthropic MCP 入門 → Hugging Face MCP Course → 微軟 MCP for Beginners |
| 想把 AI 程式代理導入團隊 | Claude Code in Action → AI Dev Tools Zoomcamp |
| 想了解研究前沿 | 柏克萊 Agentic AI MOOC |
| 偏好中文 | Datawhale《Hello-Agents》，見 [11｜中文原生課程](11-chinese-resources.md) |

> **學習提醒**：代理系統的難點不在「串接框架」，而在**評估、除錯與可靠性**。無論選哪門課，都要養成為代理建立評估資料集、記錄執行軌跡（Trace）並做錯誤分析的習慣。

---

## 延伸清單：更多代理、MCP 與程式代理課程（2026 年 11 月增補）

### 2026 年新課與重點補充

| 課程（中文／英文） | 提供者 | 程度 | 費用 | 連結 | 說明 |
|---|---|---|---|---|---|
| 上下文課程 / The Context Course | Hugging Face | ⭐⭐ | 免費（含兩級證書） | <https://github.com/huggingface/context-course> | **程式代理的上下文工程**：技能（Skills）→ MCP → 外掛（Plugins）→ 子代理 → Hooks → 加分單元「從零打造迷你代理框架」。以 Claude Code、Codex、OpenCode 三種代理貫穿範例 |
| 自我改進的 AI 代理 / CS329A: Self-Improving AI Agents | 史丹佛 | ⭐⭐⭐ | 免費 | <https://cs329a.stanford.edu/> | 2025 秋季授課、2026 年 8 月公開錄影；測試階段運算、驗證器、從回饋學習、規劃、深度研究代理與代理評估 |
| 評估與改進代理式應用 / Evaluating and Improving Agentic Applications | DeepLearning.AI | ⭐⭐ | 影片免費 | <https://www.deeplearning.ai/courses/> | 2026 年下半年新上架 |
| 以程式代理進行規格驅動開發 / Spec-Driven Development with Coding Agents | DeepLearning.AI | ⭐⭐ | 影片免費 | <https://www.deeplearning.ai/courses/> | 2026 年下半年新上架 |
| 打造自適應 AI 代理／AI 程式碼審查／代理的語音介面等短課 | DeepLearning.AI 與合作夥伴 | ⭐⭐ | 影片免費 | <https://www.deeplearning.ai/courses/> | 同期新上架：Building Adaptive AI Agents、AI Code Review（與 Qodo 合作）、Voice for AI Agents and Applications、Build Interactive Agents with Generative UI |
| 代理技能 / Agent Skills with Anthropic | DeepLearning.AI × Anthropic | ⭐⭐ | 影片免費 | <https://www.deeplearning.ai/short-courses/agent-skills-with-anthropic/> | 2026 年 2 月；Datawhale 有[中文整理](https://github.com/datawhalechina/agent-skills-with-anthropic) |
| Claude Code：高度代理化的程式助理 / Claude Code: A Highly Agentic Coding Assistant | DeepLearning.AI × Anthropic | ⭐⭐ | 影片免費 | <https://www.deeplearning.ai/short-courses/claude-code-a-highly-agentic-coding-assistant/> | 以三個專案示範程式代理工作流程 |
| 以 Claude 進行 AI 工程 / AI Engineering with Claude（奈米學位） | Udacity | ⭐⭐ | 付費 | <https://www.udacity.com/> | 4 門課、4 個專案 |

### 開源教學與工程指南

| 資源（中文／英文） | 提供者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| 12 要素代理 / 12-Factor Agents | HumanLayer | ⭐⭐ | <https://github.com/humanlayer/12-factor-agents> | 打造可靠 LLM 應用的 12 條工程原則：掌握自己的提示與上下文視窗、工具即結構化輸出、小而專注的代理、無狀態化等 |
| GenAI 代理教學集 / GenAI Agents | Nir Diamant | ⭐⭐ | <https://github.com/NirDiamant/GenAI_Agents> | 從簡單到進階的大量代理實作 Notebook |
| 邁向上線的代理 / Agents Towards Production | Nir Diamant | ⭐⭐～⭐⭐⭐ | <https://github.com/NirDiamant/agents-towards-production> | 狀態管理、向量記憶、部署、可觀測性、安全等上線主題 |
| 學習代理式 AI / Learn Agentic AI | Panaversity | ⭐⭐ | <https://github.com/panaversity/learn-agentic-ai> | 巴基斯坦大型培訓計畫的公開課綱，偏雲原生架構 |
| LangChain Academy：LangGraph 入門 | LangChain | ⭐⭐ | <https://github.com/langchain-ai/langchain-academy> | 模組 1–5 逐步建構 LangGraph 代理，模組 6 談部署 |
| Agentic AI 中文版 | Datawhale | ⭐⭐ | <https://github.com/datawhalechina/agentic-ai> | **中文**；吳恩達 Agentic AI 課程的翻譯、整理與程式解讀 |
| Hello-Agents／wow-agent | Datawhale | ⭐⭐ | <https://github.com/datawhalechina/hello-agents> | **中文**；見 [11](11-chinese-resources.md) |
| Anthropic 技能範例庫 / Skills | Anthropic | ⭐⭐ | <https://github.com/anthropics/skills> | 代理技能的官方範例與規格 |

### 其他平台的代理課程

| 課程 | 提供者 | 費用 | 連結 | 說明 |
|---|---|---|---|---|
| 給領導者的代理式 AI／AI Agents 專項課程 | 范德堡大學，Coursera | 部分免費 | <https://www.coursera.org/> | 不寫程式或少量程式 |
| AI Engineer Agentic Track 等 | Udemy（Ed Donner） | 付費（常態折扣） | <https://www.udemy.com/> | 多份評比中最常出現的 Udemy 代理課，含 MCP 與多個專案 |
| Copilot Studio／Azure AI Foundry 代理學習路徑 | Microsoft Learn | 免費 | <https://learn.microsoft.com/training/> | 對應 AI-103 認證（見 [12](12-certifications.md)） |
| AI Evals for Engineers & PMs | Hamel Husain、Shreya Shankar（Maven） | 付費（約 4,500 美元） | <https://maven.com/parlance-labs/evals> | 代理與 LLM 產品的評估方法，業界口碑極佳 |
| 代理與工作流程 / Agents and Workflows | OpenAI Academy | 免費 | <https://academy.openai.com/> | 2026 年 6 月上線的三門自學課之一 |
| 精通 GitHub Copilot | 微軟 | 免費 | <https://github.com/microsoft/Mastering-GitHub-Copilot-for-Paired-Programming> | 另有 GitHub Copilot 認證（GH-300） |

不寫程式建立代理（n8n、Dify、Coze、Copilot Studio）與 Vibe Coding 請見 [17｜無程式碼與創意 AI](17-nocode-creative.md)。
