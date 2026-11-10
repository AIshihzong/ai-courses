# 12｜AI 證照與認證

> 適合對象：需要在履歷上證明 AI 能力、或公司要求取得特定雲端認證的人。
> **2026 年是 AI 認證大改版的一年**：微軟 Azure 的 AI-900、AI-102 考試退役並由新考試取代；AWS 機器學習專業認證退役，新增生成式 AI 開發者專業認證；Google Cloud 推出非技術導向的生成式 AI 領導者認證；OpenAI 也開始試行官方認證。
>
> ⚠️ 考試代碼、費用與日期變動頻繁，**報名前務必以原廠官方頁面為準**。下表資訊整理自 2026 年 10 月的公開資料，部分來自第三方整理。

[← 回到總覽](../README.md)

## 速覽：雲端與原廠認證

| 廠商 | 認證（中文譯名／英文原名） | 等級 | 狀態（2026 年 10 月） | 參考費用 | 適合對象 |
|---|---|---|---|---|---|
| AWS | AI 從業人員 / AWS Certified AI Practitioner（AIF-C01） | 基礎 | 現行 | 約 100 美元 | 非技術與入門技術人員 |
| AWS | 機器學習工程師－助理級 / Machine Learning Engineer – Associate（MLA） | 助理級 | 改版中（MLA-C01 → MLA-C02） | 約 150 美元 | ML 工程師 |
| AWS | 生成式 AI 開發者－專業級 / Generative AI Developer – Professional（AIP-C01） | 專業級 | 2026 年起正式開放（Beta 已於 2026-03-31 結束） | 約 300 美元 | 資深 GenAI 開發者 |
| AWS | 機器學習－專業級 / Machine Learning – Specialty | 專業級 | **已退役**（最後考試日 2026-03-31） | — | 持有者證照自取得日起有效三年 |
| 微軟 | Azure AI 基礎 / Azure AI Fundamentals（AI-900 → **AI-901**） | 基礎 | AI-900 考試於 2026-06-30 退役，由 AI-901 取代 | 依地區而定 | 入門者 |
| 微軟 | Azure AI 應用與代理開發者－助理級 / Azure AI Apps and Agents Developer Associate（**AI-103**） | 助理級 | 取代 2026-06-30 退役的 AI-102 | 依地區而定 | Azure AI 開發者 |
| Google Cloud | 生成式 AI 領導者 / Generative AI Leader | 基礎 | 現行 | 約 99 美元（90 分鐘） | 任何職務，無先備條件 |
| Google Cloud | 專業機器學習工程師 / Professional Machine Learning Engineer | 專業級 | 現行 | 約 200 美元 | ML 工程師 |
| NVIDIA | 生成式 AI 與 LLM 認證助理 / NVIDIA-Certified Associate: Generative AI LLMs（NCA-GENL） | 助理級 | 現行 | 125 美元（官網；50 題、60 分鐘） | LLM 應用開發入門 |
| OpenAI | OpenAI 認證 / OpenAI Certifications | — | 邀請制試行（企業與教育機構） | — | 尚未對一般大眾開放 |
| Anthropic | Claude 認證（助理、開發者、架構師共四項） | 基礎～專業 | 僅限 Claude 合作夥伴網路成員組織 | 99–175 美元 | 合作夥伴公司的員工 |

---

## AWS 認證

- **官方頁面**：<https://aws.amazon.com/certification/>
- **免費備考資源**：AWS Skill Builder <https://skillbuilder.aws/>

**重點整理**：
- **AI Practitioner（AIF-C01）**：AI／ML 與生成式 AI 的基礎概念、AWS 相關服務（如 Amazon Bedrock、SageMaker）、負責任 AI 與安全治理。適合業務、PM 與入門技術人員。
- **Machine Learning Engineer – Associate**：資料準備、模型開發、部署與維運、監控與安全。據第三方資料，新版 MLA-C02 將加入生成式 AI、代理式 AI 與 LLM 工作負載，正式版預計 2027 年初推出（日期以 AWS 公告為準）。
- **Generative AI Developer – Professional（AIP-C01）**：針對具備 2 年以上 AWS 開發經驗、1 年以上生成式 AI 實務經驗的開發者。考試領域包括基礎模型整合／資料管理與合規（31%）、實作與整合（26%）、AI 安全／資安與治理（20%）、營運效率與最佳化（12%）、測試驗證與除錯（11%）。標準版已加入 Amazon Bedrock AgentCore 等新服務。
- **Machine Learning – Specialty**：已退役，原有持有者的證照自取得日起三年內仍有效。

---

## 微軟 Azure 認證

- **官方頁面**：<https://learn.microsoft.com/credentials/>
- **免費備考資源**：Microsoft Learn 學習路徑（免費）

**重點整理**：
- **AI-900 → AI-901**：AI-900 考試於 2026 年 6 月 30 日退役，Azure AI Fundamentals 認證本身並未取消；基礎級認證**永久有效**，已持有者無需任何動作。新考生改考 AI-901。
- **AI-102 → AI-103**：AI-102（Azure AI Engineer Associate）同日退役，取而代之的是 **AI-103：Azure AI Apps and Agents Developer Associate**，內容圍繞生成式 AI、代理式應用與以 **Microsoft Foundry** 及 Azure 服務打造 RAG 解決方案。
- 助理級認證需每年透過 Microsoft Learn 免費線上評量續期。
- **新的商務與架構認證**：微軟另推出不需寫程式的 **AB-730（AI Business Professional）** 與 **AB-731（AI Transformation Leader）**，第三方資料列為 99 美元、45 分鐘；以及專家級的 **AB-100（Agentic AI Business Solutions Architect）**，需先具備 AI-103 等助理級認證。
- **DP-100 → AI-300**：Azure 資料科學家認證 DP-100 也在 2026 年退役，由 AI-300 取代（依第三方整理，日期以 Microsoft Learn 為準）。
- 2026 年微軟將 Azure AI Foundry 更名為 **Microsoft Foundry**，考綱用語隨之更新。

---

## Google Cloud 認證

- **官方頁面**：<https://cloud.google.com/learn/certification>
- **免費備考資源**：Google Skills <https://www.skills.google/>

**重點整理**：
- **Generative AI Leader**：面向非技術人員的生成式 AI 策略與應用認證，無先備條件。
- **Professional Machine Learning Engineer**：涵蓋 ML 問題框架、資料準備、模型開發、MLOps 與 Vertex AI 上的生成式 AI 解決方案。

---

## NVIDIA 認證

- **官方頁面**：<https://www.nvidia.com/en-us/learn/certification/>

**重點整理**：
- **NCA-GENL**：驗證開發、整合與維護 LLM 應用的基礎能力。官方建議的備考資源包括免費自學課程（如以 RAG 強化 LLM）。課程與考試費用分開計算。
- 專業級另有 **NCP-GENL**（Generative AI LLMs，約 200 美元、120 分鐘）與 **NCP-AAI**（Agentic AI，約 200 美元）；另有多模態（NCA-GENM）與 AI 基礎設施等方向。各地區上線時程不一，以 NVIDIA 認證頁為準。

---

## OpenAI 認證

- **相關頁面**：<https://academy.openai.com/>

**重點整理**：
- OpenAI Academy 的免費課程完成後可取得**結業證明**，但 OpenAI 明確表示這**不是正式的 OpenAI 認證**，也不保證未來的認證資格。
- 正式的 **OpenAI Certifications** 截至 2026 年仍是針對 ChatGPT Enterprise／Edu 工作區的邀請制試行計畫，尚未對一般大眾開放。

---

## 台灣：iPAS AI 應用規劃師能力鑑定

- **主辦單位**：經濟部產業發展署（iPAS 產業人才能力鑑定）
- **官方網站**：<https://www.ipas.org.tw/>

**重點整理**：
- 分為**初級**與**中級**。初級鎖定非資訊專業人士，考科涵蓋人工智慧基礎、資料處理、機器學習，以及鑑別式與生成式 AI 的基本概念。
- 採電腦測驗（單選題），每科 100 分、70 分及格。自 2025 年（民國 114 年）第二梯次起，中級部分科目加入 Python 程式相關題型。
- 近年報考人數大增，許多大專院校與企業開設備考課程。梯次、費用與證書效期請以官方最新簡章為準。

**點評**：台灣本地辨識度高的 AI 能力證明，適合求職或公部門、企業內部認可需求。

---

## 課程平台證書

除了原廠認證，許多課程平台也提供「完課證書」：

| 平台 | 證書類型 | 費用 |
|---|---|---|
| Coursera | 單門課程證書、專項課程證書、專業證書（Professional Certificate，如 IBM、Google） | 需付費（Coursera Plus 或單門購買） |
| DeepLearning.AI | 課程與專項證書 | 需 DeepLearning.AI Pro 會員 |
| edX | 認證證書（Verified Certificate） | 需付費 |
| Hugging Face | 各課程完課證書 | 免費 |
| Claude Academy（原 Anthropic Academy） | 完課證明 | 免費 |
| Kaggle Learn | 微課程證書 | 免費 |
| Elements of AI | 赫爾辛基大學證書 | 免費 |
| DataTalksClub Zoomcamp | 完成專案後的證書 | 免費 |

---

## 證照到底有沒有用？

1. **原廠認證（AWS／Azure／Google Cloud）**：在需要特定雲端技能的職缺（顧問、系統整合商、雲端團隊）中有實際篩選作用，也常是企業與原廠合作夥伴資格的要求。
2. **課程完課證書**：證明你「上過課」，但對技術職缺的說服力有限。
3. **最有說服力的永遠是作品**：GitHub 專案、部署上線的應用、Kaggle 成績、技術部落格或開源貢獻。

> **建議**：把證照當作「學習的結構與里程碑」，而不是目的。優先投資時間在能展示的實作專案上。詳見 [學習路線圖](../docs/learning-paths.md) 中各路線的里程碑專案。

---

## 延伸清單：更多 AI 認證（2026 年 11 月增補）

> 以下價格與題數多取自 2026 年的第三方整理，不同來源常有出入，**報名前請以原廠頁面為準**。

### Anthropic：Claude 認證

- 2026 年 3 月隨 **Claude 合作夥伴網路（Claude Partner Network）** 推出，首項為「Claude Certified Architect – Foundations」；其後擴充為四項監考考試：

| 認證 | 參考費用 | 對象 |
|---|---|---|
| Claude Certified Associate – Foundations | 99 美元 | 一般使用與基礎知識 |
| Claude Certified Developer – Foundations | 125 美元 | 以 Claude 開發（含 Claude Code 與 MCP） |
| Claude Certified Architect – Foundations | 125 美元 | 解決方案架構 |
| Claude Certified Architect – Professional | 175 美元 | 進階架構 |

- 考試透過 Pearson VUE 進行，每場 120 分鐘，及格分數 720／1000。
- **重要限制**：目前僅開放給**已加入合作夥伴網路的組織**成員報名，個人（以私人信箱）無法註冊。一般學習者可先修 [Claude Academy](https://academy.claude.com/courses) 的免費課程並取得完課證明。

### 資料與企業軟體平台

| 廠商 | 認證 | 參考費用／形式 | 官方頁面 | 說明 |
|---|---|---|---|---|
| Databricks | Generative AI Engineer Associate | 約 200 美元；90 分鐘、45 題 | <https://www.databricks.com/learn/certification> | 在 Databricks 上建置 LLM 應用；建議 6 個月以上實務經驗 |
| Oracle | OCI AI Foundations Associate | **免費**（60 分鐘；有來源列為 95 美元） | <https://education.oracle.com/> | 目前最容易取得的免費原廠認證之一；Oracle 表示基礎級課程與認證維持免費 |
| Salesforce | Agentforce Specialist | 約 200 美元；60 題、105 分鐘 | <https://trailhead.salesforce.com/> | 取代已於 2026 年 2 月退役的 AI Associate |
| GitHub | GitHub Copilot（GH-300） | 約 99 美元；約 60 題、100 分鐘 | <https://resources.github.com/learn/certifications/> | 另有測試中的 Agentic AI Developer 專業考試 |
| Snowflake | SnowPro Specialty: Gen AI | 約 225–375 美元（來源不一） | <https://www.snowflake.com/certifications/> | 建議一年以上 Snowflake 經驗 |
| IBM | watsonx Generative AI Engineer – Associate | 依官網 | <https://www.ibm.com/training/> | 提示調校、微調與 RAG；另有 Coursera 專業證書與免費的 SkillsBuild 徽章 |

### AI 治理、風險與資安

| 發證單位 | 認證 | 對象 | 官方頁面 | 說明 |
|---|---|---|---|---|
| IAPP | AI 治理專業人員 / Artificial Intelligence Governance Professional（AIGP） | 法遵、隱私、風險管理人員 | <https://iapp.org/certify/aigp/> | 治理領域最通用的證照；100 題選擇題、四大領域，無先備條件；知識體系於 2026 年 2 月更新至 2.1 版 |
| ISACA | AAIA（AI 稽核）、AAISM（AI 安全管理）、AAIR（AI 風險） | 稽核與資安主管 | <https://www.isaca.org/credentialing> | 2025–2026 年推出的進階系列，需先持有 CISA、CISM 等既有證照 |
| CompTIA | SecAI+（CY0-001） | 資安從業人員 | <https://www.comptia.org/> | 2026 年 2 月推出，廠商中立；涵蓋保護 AI 系統、在資安維運中應用 AI，以及治理與風險 |
| PMI | PMI-CPMAI（AI 專案管理） | 專案與產品經理 | <https://www.pmi.org/> | 120 題、160 分鐘，需先修官方課程 |
| PECB 等 | ISO/IEC 42001 主導實施人員／主導稽核員 | AI 管理系統建置與稽核人員 | <https://pecb.com/> | 個人證照；與「組織通過 ISO 42001 驗證」是兩回事 |
| OffSec | AI 紅隊認證（OSAI） | 攻擊性資安人員 | <https://www.offsec.com/> | 2026 年推出的新認證（依第三方報導，細節以官網為準） |

### 中國大陸

| 認證 | 發證單位 | 說明 |
|---|---|---|
| 大模型工程師 ACA／大模型高級工程師 ACP | 阿里雲（<https://edu.aliyun.com/certification/llm>） | 取代已於 2025 年 11 月下線的「人工智能工程師 ACA／ACP」；ACA 面向非技術背景與初學者，ACP 面向有程式基礎的應用開發者 |
| HCIA-AI／HCIP-AI／HCIE-AI | 華為 | 華為 AI 認證體系的初、中、高三級；2026 年考綱更新，報名前請確認最新考試代碼 |
| 人工智能訓練師（職業技能等級，五級至一級） | 人社部門備案的評價機構 | 國家職業技能等級認定；多數地區需透過評價機構報名，梯次與費用各地不同 |

### 免費就能拿到的證書（速查）

| 證書 | 提供者 | 類型 |
|---|---|---|
| Elements of AI 證書 | 赫爾辛基大學 | 完課證書 |
| Claude Academy 各課程證明 | Anthropic | 完課證明 |
| OpenAI Academy 課程證明 | OpenAI | 完課證明（非正式認證） |
| Hugging Face 課程證書（Agents、Context、smol、Deep RL、Audio 等） | Hugging Face | 完課證書 |
| Kaggle Learn 微課程證書 | Kaggle | 完課證書 |
| Google Skills 技能徽章 | Google | 徽章（部分實驗室需點數） |
| IBM SkillsBuild 數位徽章 | IBM | 徽章 |
| DataTalksClub Zoomcamp 證書 | DataTalksClub | 完成專案後頒發 |
| OCI AI Foundations Associate | Oracle | **正式監考認證**（免費） |
| Microsoft Learn 應用技能／完成徽章 | 微軟 | 徽章（正式認證考試需付費） |
