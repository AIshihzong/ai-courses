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
| NVIDIA | 生成式 AI 與 LLM 認證助理 / NVIDIA-Certified Associate: Generative AI LLMs（NCA-GENL） | 助理級 | 現行 | 約 135 美元（1 小時） | LLM 應用開發入門 |
| OpenAI | OpenAI 認證 / OpenAI Certifications | — | 邀請制試行（企業與教育機構） | — | 尚未對一般大眾開放 |

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
- NVIDIA 另有多模態、AI 基礎設施等不同方向的助理級與專業級認證，可依需求選擇。

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
| Anthropic Academy | 完課證書 | 免費 |
| Kaggle Learn | 微課程證書 | 免費 |
| Elements of AI | 赫爾辛基大學證書 | 免費 |
| DataTalksClub Zoomcamp | 完成專案後的證書 | 免費 |

---

## 證照到底有沒有用？

1. **原廠認證（AWS／Azure／Google Cloud）**：在需要特定雲端技能的職缺（顧問、系統整合商、雲端團隊）中有實際篩選作用，也常是企業與原廠合作夥伴資格的要求。
2. **課程完課證書**：證明你「上過課」，但對技術職缺的說服力有限。
3. **最有說服力的永遠是作品**：GitHub 專案、部署上線的應用、Kaggle 成績、技術部落格或開源貢獻。

> **建議**：把證照當作「學習的結構與里程碑」，而不是目的。優先投資時間在能展示的實作專案上。詳見 [學習路線圖](../docs/learning-paths.md) 中各路線的里程碑專案。
