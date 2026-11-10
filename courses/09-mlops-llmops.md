# 09｜MLOps、LLMOps 與 AI 系統工程

> 適合對象：想把模型或 LLM 應用**可靠地部署到生產環境**、並持續監控與改進的工程師；以及對 GPU、訓練與推論系統有興趣的人。
> 很多 AI 專案失敗不是因為模型不夠好，而是因為缺乏資料管線、評估、監控與部署能力。這一類課程補的正是這塊。

[← 回到總覽](../README.md)

## 速覽

| # | 課程（中文譯名／英文原名） | 提供者 | 程度 | 費用 | 重點 |
|---|---|---|---|---|---|
| 1 | 用機器學習打造產品 / Made With ML | Goku Mohandas | ⭐⭐ | 免費 | 端到端 MLOps |
| 2 | MLOps Zoomcamp | DataTalksClub | ⭐⭐ | 免費 | 實驗追蹤到監控 |
| 3 | LLM Zoomcamp | DataTalksClub | ⭐⭐ | 免費 | RAG 系統與評估 |
| 4 | 生產環境中的機器學習 / Machine Learning in Production | DeepLearning.AI（吳恩達） | ⭐⭐ | 部分免費 | 專案生命週期 |
| 5 | 全端深度學習 / Full Stack Deep Learning | FSDL | ⭐⭐ | 免費（已封存） | 部署與 LLM 應用 |
| 6 | 史丹佛 CS329S 機器學習系統設計 / ML Systems Design | 史丹佛大學（Chip Huyen） | ⭐⭐ | 免費（已封存） | 系統設計思維 |
| 7 | 卡內基美隆深度學習系統 / Deep Learning Systems | CMU | ⭐⭐⭐ | 免費 | 從零寫深度學習框架 |
| 8 | GPU MODE 講座 / GPU MODE Lectures | GPU MODE 社群 | ⭐⭐⭐ | 免費 | CUDA、Triton、效能 |
| 9 | NVIDIA DLI 部署與加速運算課程 | NVIDIA | ⭐⭐～⭐⭐⭐ | 部分免費 | 推論部署 |

---

## 1. 用機器學習打造產品（Made With ML）

- **提供者**：Goku Mohandas
- **程度**：⭐⭐ 中級｜**費用**：免費開源
- **連結**：<https://madewithml.com/>

**簡介**：從「設計 → 資料 → 模型 → 開發 → 部署 → 迭代」完整走一次機器學習產品的開發流程，涵蓋分散式訓練、實驗追蹤、測試、CI/CD、服務化與監控。

**點評**：GitHub 上最受歡迎的 MLOps 教材之一，強調軟體工程最佳實務。適合已會訓練模型、想學「如何做成產品」的人。

---

## 2. MLOps Zoomcamp

- **提供者**：DataTalksClub（Alexey Grigorev）
- **程度**：⭐⭐ 中級｜**費用**：免費（完成專案可取得證書）
- **連結**：<https://github.com/DataTalksClub/mlops-zoomcamp>

**主題**：實驗追蹤與模型註冊（MLflow）、工作流程編排、模型部署（批次、網路服務、串流）、模型監控、最佳實務（測試、IaC、CI/CD）。

**點評**：社群活躍、實作導向，課程影片與作業全年可自學。2026 年直播梯次日期截至本文整理時尚未公布。

---

## 3. LLM Zoomcamp

- **提供者**：DataTalksClub
- **程度**：⭐⭐ 中級｜**費用**：免費（完成專案可取得證書）
- **連結**：<https://github.com/DataTalksClub/llm-zoomcamp>

**簡介**：以託管 LLM 打造**生產等級的 RAG 系統**，並學習評估與上線監控。2026 年梯次於 6 月至夏末進行。

**2026 年版模組**：代理式 RAG → 向量搜尋 → 編排（Orchestration）→ 評估 → 監控 → 最佳實務 → 端到端專案範例，最後以結業專案收尾；另有資料擷取工作坊。

**點評**：是少數完整談到「RAG 系統評估與監控」的免費課程，強烈推薦給要把 LLM 應用上線的工程師。

---

## 4. 生產環境中的機器學習（Machine Learning in Production）

- **提供者**：DeepLearning.AI，吳恩達主講
- **程度**：⭐⭐ 中級｜**費用**：Coursera 首個模組可免費預覽，完整內容與證書需付費（可申請助學金）
- **連結**：<https://www.coursera.org/learn/introduction-to-machine-learning-in-production>

**簡介**：介紹機器學習專案的完整生命週期：範疇界定、資料定義與基準、建模與誤差分析、部署模式、概念漂移與資料漂移、監控。

**點評**：偏重觀念與方法論，適合作為 MLOps 的第一門課，再銜接第 1–2 項的實作課程。

---

## 5. 全端深度學習（Full Stack Deep Learning）

- **提供者**：Full Stack Deep Learning 團隊（Charles Frye、Sergey Karayev、Josh Tobin 等）
- **程度**：⭐⭐｜**費用**：免費（2022 年課程與 2023 年 LLM Bootcamp 已封存）
- **連結**：<https://fullstackdeeplearning.com/>

**點評**：雖然不再更新，但關於專案管理、資料管理、部署、監控，以及 LLM Bootcamp 中的提示工程、增強語言模型、LLMOps 等講座仍有很高的參考價值。

---

## 6. 史丹佛 CS329S：機器學習系統設計（Machine Learning Systems Design）

- **提供者**：史丹佛大學，Chip Huyen
- **程度**：⭐⭐｜**費用**：投影片與筆記免費（已封存）
- **連結**：<https://stanford-cs329s.github.io/>

**延伸閱讀**：Chip Huyen 的著作《Designing Machine Learning Systems》與《AI Engineering》（O'Reilly 出版）是本領域的重要參考書。

**點評**：系統設計思維的優秀教材，適合準備 MLE 面試或負責 AI 系統架構的工程師。

---

## 7. 卡內基美隆深度學習系統（10-414/714: Deep Learning Systems）

- **提供者**：卡內基美隆大學，陳天奇、Zico Kolter
- **程度**：⭐⭐⭐ 進階｜**費用**：線上版錄影與作業免費
- **連結**：<https://dlsyscourse.org/>

**簡介**：從零實作一個深度學習框架（needle）：自動微分、神經網路函式庫、硬體加速（CPU/GPU）、卷積、序列模型等。

**點評**：想理解 PyTorch 等框架「底層到底發生了什麼」的最佳課程。

---

## 8. GPU MODE 講座（GPU MODE Lectures）

- **提供者**：GPU MODE 社群
- **程度**：⭐⭐⭐ 進階｜**費用**：免費（YouTube + GitHub）
- **連結**：<https://github.com/gpu-mode/lectures>

**簡介**：社群主辦的系列講座，主題包括 CUDA 程式設計、Triton、效能分析、FlashAttention、量化、分散式訓練等。

**點評**：LLM 時代「效能工程」人才非常稀缺，這是自學 GPU 程式設計的最佳社群資源之一。可與史丹佛 CS336 的系統相關單元搭配。

---

## 9. NVIDIA DLI 部署與加速運算課程

- **提供者**：NVIDIA 深度學習學院
- **程度**：⭐⭐～⭐⭐⭐｜**費用**：部分自學課程免費，進階課程與講師帶領工作坊付費
- **連結**：<https://www.nvidia.com/en-us/training/>

**主題範例**：NVIDIA NIM 微服務部署、CUDA 加速運算基礎、LLM 推論最佳化、多 GPU 訓練。

**點評**：若生產環境使用 NVIDIA GPU，官方課程能最快學到工具鏈的正確用法；部分課程附帶雲端 GPU 實作環境。

---

## 本類別選課建議

| 你的目標 | 建議路線 |
|---|---|
| 傳統 ML 模型上線 | Machine Learning in Production（觀念）→ Made With ML 或 MLOps Zoomcamp（實作） |
| LLM 應用上線 | LLM Zoomcamp → Full Stack Deep Learning LLM Bootcamp 講座 |
| 系統設計／面試 | CS329S + Chip Huyen 著作 |
| 底層效能工程 | CMU Deep Learning Systems → GPU MODE → 史丹佛 CS336 系統單元 |

---

## 延伸清單：更多 MLOps、評估與系統課程（2026 年 11 月增補）

### 評估與可觀測性（目前最缺人才的能力）

| 課程（中文／英文） | 提供者 | 程度 | 費用 | 連結 | 說明 |
|---|---|---|---|---|---|
| 給工程師與 PM 的 AI 評估 / AI Evals for Engineers & PMs | Hamel Husain、Shreya Shankar（Maven） | ⭐⭐ | 付費（約 4,500 美元） | <https://maven.com/parlance-labs/evals> | 錯誤分析、評審模型校準、評估流程設計；2026 年仍持續開梯次 |
| LLM 評估指南 / LLM Evaluation Guidebook | Hugging Face | ⭐⭐ | 免費 | <https://github.com/huggingface/evaluation-guidebook> | 評估方法、設計自己的評估、常見陷阱 |
| ML 可觀測性／LLM 評估開放課程 | Evidently AI | ⭐⭐ | 免費 | <https://www.evidentlyai.com/courses> | 資料漂移、模型監控與 LLM 評估的實作課 |
| W&B AI 學院 | Weights & Biases | ⭐⭐ | 免費 | <https://www.wandb.courses/> | 實驗追蹤、LLM 應用評估、微調 |
| LangSmith 入門 / Intro to LangSmith | LangChain | ⭐⭐ | 免費 | <https://github.com/langchain-ai/intro-to-langsmith> | 追蹤、資料集與評估 |

### ML 與 LLM 系統

| 課程（中文／英文） | 提供者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| 機器學習系統 / CMU 15-442／642 | CMU（陳天奇） | ⭐⭐⭐ | <https://mlsyscourse.org/> | 自動微分、分散式訓練、編譯器作業 |
| 大型語言模型系統 / CMU 11-868 | CMU | ⭐⭐⭐ | <https://llmsystem.github.io/llmsystem2025spring/> | GPU 加速、分散式訓練與推論 |
| 機器學習的資料系統 / CSE234 | UC San Diego | ⭐⭐⭐ | <https://hao-ai-lab.github.io/cse234-w25/> | LLM 訓練與推論系統，影片公開 |
| TinyML 與高效深度學習運算 / MIT 6.5940 | MIT（韓松） | ⭐⭐⭐ | <https://hanlab.mit.edu/courses/2024-fall-65940> | 量化、剪枝、蒸餾與高效推論 |
| 機器學習系統（開源教科書） | 哈佛 CS249r | ⭐⭐～⭐⭐⭐ | <https://mlsysbook.ai/> | 從嵌入式到資料中心 |
| 機器學習編譯 / Machine Learning Compilation | 陳天奇（MLC） | ⭐⭐⭐ | <https://mlc.ai/> | 模型編譯與部署，有中文版 |
| 史丹佛 MLSys 研討會 / Stanford MLSys Seminars | 史丹佛 | ⭐⭐⭐ | [YouTube](https://www.youtube.com/playlist?list=PLSrTvUm384I9PV10koj_cqit9OfbJXEkq) | 業界與學界的系統講座 |
| 機器學習工程開放書 / ML Engineering Open Book | Stas Bekman | ⭐⭐⭐ | <https://github.com/stas00/ml-engineering> | 大規模訓練的硬體、除錯與效能實戰筆記 |
| 智能計算系統 | 中國科學院大學 | ⭐⭐⭐ | <https://novel.ict.ac.cn/aics/> | **中文**；從 AI 晶片到框架的全棧課程 |
| 機器學習系統：設計和實現 | OpenMLSys | ⭐⭐⭐ | <https://openmlsys.github.io/> | **中文**開源教材 |

### 工程實務與資料

| 課程（中文／英文） | 提供者 | 程度 | 費用 | 連結 | 說明 |
|---|---|---|---|---|---|
| 機器學習 Zoomcamp | DataTalksClub | ⭐⭐ | 免費 | <https://github.com/DataTalksClub/machine-learning-zoomcamp> | 模型訓練到部署（Docker、Kubernetes、Serverless） |
| 資料工程 Zoomcamp | DataTalksClub | ⭐⭐ | 免費 | <https://github.com/DataTalksClub/data-engineering-zoomcamp> | 資料管線、倉儲、批次與串流 |
| MLOps／LLMOps 專項課程 | 杜克大學（Noah Gift），Coursera | ⭐⭐ | 部分免費 | <https://www.coursera.org/> （搜尋 "Duke MLOps"） | 雲端平台與 Rust／Python 的 MLOps 實務 |
| 以資料為中心的 AI 導論 | MIT | ⭐⭐ | 免費 | <https://dcai.csail.mit.edu/> | 標註錯誤、資料品質 |
| 邁向上線的代理 / Agents Towards Production | Nir Diamant | ⭐⭐～⭐⭐⭐ | 免費 | <https://github.com/NirDiamant/agents-towards-production> | 代理系統的部署、記憶、可觀測性與安全 |
| LLM 分身課程 / LLM Twin Course | Decoding ML | ⭐⭐⭐ | 免費 | <https://github.com/decodingml/llm-twin-course> | 端到端 LLM 系統：資料管線、微調、RAG、監控 |

邊緣裝置與小模型部署見 [14｜垂直領域](14-domain-applications.md#b-邊緣-ai-與高效推論)。
