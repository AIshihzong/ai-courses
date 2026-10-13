# 05｜生成式 AI 應用開發與提示工程

> 適合對象：想用 LLM API 打造應用程式的開發者（不一定要會訓練模型）。
> 這一類課程的核心是「**AI 工程（AI Engineering）**」：提示工程、結構化輸出、函式呼叫（Function Calling）、檢索增強生成（RAG）、評估與上線。各大模型廠商在 2025–2026 年紛紛推出官方學院，免費課程數量大增。

[← 回到總覽](../README.md)

## 速覽

| # | 課程（中文譯名／英文原名） | 提供者 | 程度 | 費用 | 重點 |
|---|---|---|---|---|---|
| 1 | 給開發者的 ChatGPT 提示工程 / ChatGPT Prompt Engineering for Developers | DeepLearning.AI × OpenAI | ⭐ | 免費 | 提示工程入門經典 |
| 2 | 互動式提示工程教學 / Prompt Engineering Interactive Tutorial | Anthropic | ⭐～⭐⭐ | 免費（GitHub） | 系統化提示技巧 |
| 3 | Anthropic 學院開發者課程 / Claude Platform 101 等 | Anthropic | ⭐⭐ | 免費（含證書） | Claude API 開發 |
| 4 | 給初學者的生成式 AI / Generative AI for Beginners | 微軟 | ⭐～⭐⭐ | 免費（GitHub） | 21 課完整應用開發 |
| 5 | 檢索增強生成 / Retrieval Augmented Generation (RAG) | DeepLearning.AI | ⭐⭐ | 部分免費 | RAG 系統設計 |
| 6 | 開發者生成式 AI 學習路徑 / Generative AI for Developers | Google Skills | ⭐⭐ | 免費為主 | Gemini 與 Google Cloud |
| 7 | OpenAI 學院應用 AI 基礎 / Applied AI Foundations | OpenAI | ⭐～⭐⭐ | 免費 | OpenAI 工具應用 |
| 8 | NVIDIA DLI 生成式 AI 技術課 | NVIDIA | ⭐⭐ | 部分免費 | RAG、NIM、LLM 應用 |
| 9 | IBM RAG 與代理式 AI 專業證書 / IBM RAG and Agentic AI Professional Certificate | IBM（Coursera） | ⭐⭐ | 付費訂閱 | 職涯導向證書 |

---

## 1. 給開發者的 ChatGPT 提示工程（ChatGPT Prompt Engineering for Developers）

- **提供者**：DeepLearning.AI × OpenAI，Isa Fulford、吳恩達主講
- **程度**：⭐ 入門｜**費用**：免費｜**時長**：約 1.5 小時
- **連結**：<https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/>

**簡介**：2023 年引爆「提示工程」學習熱潮的短課，教你透過 API 撰寫有效提示，完成摘要、推論、轉換、擴寫與聊天機器人等任務。

**點評**：雖然模型已大幅進步，但「清楚指示、給予思考空間、迭代改進」等原則依然適用。可作為 LLM 應用開發的第一堂課。中文版可參考 Datawhale 的 *llm-cookbook* 翻譯。

---

## 2. 互動式提示工程教學（Prompt Engineering Interactive Tutorial）

- **提供者**：Anthropic
- **程度**：⭐～⭐⭐｜**費用**：免費開源
- **連結**：<https://github.com/anthropics/prompt-eng-interactive-tutorial>
- **相關**：Anthropic 課程合集 <https://github.com/anthropics/courses>（API 基礎、提示評估、工具使用、真實世界提示等）

**簡介**：9 個章節搭配練習與附錄，系統化介紹提示結構、角色設定、資料與指令分離、輸出格式、逐步思考（Chain of Thought）、少樣本範例（Few-shot）、避免幻覺、複雜提示建構等。

**點評**：目前最完整的免費提示工程教材之一，練習題設計扎實。雖以 Claude 示範，但技巧可通用於其他模型。

---

## 3. Anthropic 學院開發者課程（Anthropic Academy / Claude Academy）

- **提供者**：Anthropic
- **程度**：⭐⭐ 中級｜**費用**：免費，完成可取得證書
- **連結**：<https://academy.claude.com/courses>

**簡介**：Anthropic 官方學院的開發者課程線。依官方課程頁，主要包括：

| 課程 | 說明 |
|---|---|
| Claude 平台 101（Claude Platform 101） | 從頭學習在 Claude 平台上開發，取代舊版的「Building with the Claude API」 |
| Claude Code 實戰（Claude Code in Action） | 見 [06｜AI 代理](06-ai-agents.md) |
| MCP 入門／進階（Introduction to MCP / MCP: Advanced Topics） | 見 [06｜AI 代理](06-ai-agents.md) |
| AI 流暢力（AI Fluency） | 見 [01｜AI 通識](01-ai-literacy.md) |

**點評**：課程數量自 2026 年初持續增加，內容由第一方撰寫、與產品更新同步。注意課程會隨產品改版而汰換，請以官方頁面為準。

---

## 4. 給初學者的生成式 AI（Generative AI for Beginners）

- **提供者**：微軟
- **程度**：⭐～⭐⭐｜**費用**：免費開源｜**時長**：21 課
- **連結**：<https://github.com/microsoft/generative-ai-for-beginners>

**簡介**：微軟最受歡迎的 GitHub 課綱之一，每課包含影片、說明文件與 Python/TypeScript 範例程式。提供包含中文在內的多國語言翻譯。

**主題涵蓋**：生成式 AI 與 LLM 簡介、模型選擇、負責任 AI、提示工程（基礎與進階）、文字生成應用、聊天應用、搜尋應用與向量資料庫、影像生成、低程式碼應用、函式呼叫、使用者體驗設計、安全性、應用生命週期、RAG、開源模型、AI 代理、微調、小型語言模型等。

**點評**：涵蓋面極廣，是 LLM 應用開發的「完整地圖」。微軟建議想學 AI 代理的開發者先完成本課程，再接續 *AI Agents for Beginners*。

---

## 5. 檢索增強生成（Retrieval Augmented Generation, RAG）

- **提供者**：DeepLearning.AI（Coursera）
- **程度**：⭐⭐ 中級｜**費用**：Coursera 首個模組可免費預覽，完整內容與證書需付費（可申請助學金）
- **連結**：<https://www.coursera.org/learn/retrieval-augmented-generation-rag>

**簡介**：系統化介紹 RAG 系統的各個元件：檢索器設計（關鍵字、語意與混合搜尋）、向量資料庫、分塊（Chunking）策略、重新排序、提示組裝、評估與生產環境監控。

**點評**：RAG 仍是企業導入 LLM 最常見的架構。相較於零散的短課，這門課提供較完整的系統觀。

---

## 6. 開發者生成式 AI 學習路徑（Generative AI for Developers）

- **提供者**：Google（Google Skills）
- **程度**：⭐⭐ 中級｜**費用**：多數課程免費，部分實作實驗室需點數或訂閱
- **連結**：<https://www.skills.google/>

**簡介**：Google 針對開發者的進階路徑，涵蓋影像生成、編碼器-解碼器架構、注意力機制、Transformer 與 BERT、Vertex AI 與 Gemini 應用開發等。

**點評**：適合使用 Google Cloud 或 Gemini 生態系的開發者。建議先完成 [01｜AI 通識](01-ai-literacy.md) 中的 Google 入門路徑。

---

## 7. OpenAI 學院：應用 AI 基礎（Applied AI Foundations）

- **提供者**：OpenAI
- **程度**：⭐～⭐⭐｜**費用**：免費
- **連結**：<https://academy.openai.com/>

**點評**：OpenAI 官方自學路徑中偏應用的一環，適合以 ChatGPT 與 OpenAI 平台為主要工具的團隊。詳見 [01｜AI 通識](01-ai-literacy.md)。

---

## 8. NVIDIA DLI 生成式 AI 技術課程

- **提供者**：NVIDIA 深度學習學院
- **程度**：⭐⭐ 中級｜**費用**：部分自學課程免費，講師帶領工作坊付費
- **連結**：<https://www.nvidia.com/en-us/learn/ai-learning-essentials/>

**免費課程範例**：
- 以 LLM 打造 RAG 代理（Building RAG Agents with LLMs）
- 以檢索增強生成強化你的 LLM（Augmenting Your LLM Using Retrieval-Augmented Generation）
- NVIDIA NIM 微服務入門（Introduction to NVIDIA NIM Microservices）

**點評**：偏重部署與加速，適合準備 NVIDIA 認證（如 NCA-GENL，見 [12｜認證](12-certifications.md)）或在 NVIDIA 生態系開發的工程師。

---

## 9. IBM RAG 與代理式 AI 專業證書（IBM RAG and Agentic AI Professional Certificate）

- **提供者**：IBM（Coursera）
- **程度**：⭐⭐｜**費用**：Coursera 訂閱制
- **連結**：<https://www.coursera.org/> （搜尋 "IBM RAG and Agentic AI"）

**點評**：職涯導向的多課程證書，結構完整、作業評分明確。若預算允許且需要可列在履歷上的證書，可以考慮；若只求學會技術，免費資源已足夠。

---

## 本類別選課建議

| 你的情況 | 建議組合 |
|---|---|
| 剛開始做 LLM 應用 | DeepLearning.AI 提示工程短課 → 微軟 Generative AI for Beginners |
| 要把提示寫到專業等級 | Anthropic 互動式提示教學 + Anthropic courses 倉庫 |
| 公司要導入 RAG | DeepLearning.AI RAG 課程 → LLM Zoomcamp（見 [09｜MLOps](09-mlops-llmops.md)） |
| 綁定特定雲端 | Google → Google Skills；Azure → 微軟課綱與 Microsoft Learn；AWS → AWS Skill Builder；NVIDIA → DLI |
| 下一步 | 進入 [06｜AI 代理與 MCP](06-ai-agents.md) |
