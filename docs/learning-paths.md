# AI 學習路線圖

> 依不同背景與目標，整理 7 條學習路線。每條路線都包含**階段、推薦課程、估計時間與里程碑專案**。
> 時間估算以「每週投入 8–10 小時」為基準；請依自身狀況調整。課程詳細介紹請點連結查看。

[← 回到總覽](../README.md)

## 路線總覽

| 路線 | 適合對象 | 估計時間 | 程式需求 |
|---|---|---|---|
| [A. 職場 AI 應用者](#路線-a職場-ai-應用者) | 非技術背景上班族、主管 | 4–6 週 | 不需要 |
| [B. AI 應用工程師](#路線-bai-應用工程師) | 軟體工程師轉 AI 應用開發 | 3–4 個月 | 需要 |
| [C. AI 代理工程師](#路線-cai-代理工程師) | 想專精 Agent 系統的開發者 | 2–3 個月（接續 B） | 需要 |
| [D. 機器學習／深度學習扎根](#路線-d機器學習深度學習扎根) | 想真正懂原理的工程師、學生 | 6–9 個月 | 需要 |
| [E. LLM 研究與模型訓練](#路線-ellm-研究與模型訓練) | 想做模型訓練、研究的人 | 6–12 個月（接續 D） | 需要（進階） |
| [F. MLOps／LLMOps 工程師](#路線-fmlopsllmops-工程師) | 後端／DevOps 工程師 | 3–4 個月 | 需要 |
| [G. 全中文學習路線](#路線-g全中文學習路線) | 偏好中文的學習者 | 6–12 個月 | 需要 |

---

## 路線 A：職場 AI 應用者

**目標**：理解 AI 能做什麼、不能做什麼，並在日常工作中有效、安全地使用 AI 工具。

| 階段 | 時間 | 課程 | 連結 |
|---|---|---|---|
| 1. 建立觀念 | 第 1–2 週 | Elements of AI（前 3 章）或 AI For Everyone | [01](../courses/01-ai-literacy.md) |
| 2. 理解生成式 AI | 第 2–3 週 | Generative AI for Everyone 或 李宏毅「生成式 AI 導論 2024」前幾講 | [01](../courses/01-ai-literacy.md)、[11](../courses/11-chinese-resources.md) |
| 3. 實用技能 | 第 3–4 週 | Google AI Essentials 或 OpenAI Academy + Anthropic AI Fluency | [01](../courses/01-ai-literacy.md) |
| 4. 負責任使用 | 第 5 週 | Ethics of AI 或 Google 負責任 AI 簡介 | [10](../courses/10-ai-safety-ethics.md) |
| 5. 落地實踐 | 第 5–6 週 | 挑選工作中 3 個重複性任務，設計 AI 輔助流程並記錄效果 | — |

**里程碑專案**：為你的團隊撰寫一份「AI 使用指南」，包含 3 個經過驗證的工作流程、提示範本，以及「哪些情況不該用 AI」的清單。

**可選認證**：Google Cloud Generative AI Leader、AWS AI Practitioner、iPAS AI 應用規劃師（初級）（見 [12](../courses/12-certifications.md)）。

---

## 路線 B：AI 應用工程師

**目標**：能用 LLM API 打造可靠的應用程式（聊天機器人、RAG 系統、自動化流程）並部署上線。

**先備條件**：熟悉 Python 或 TypeScript、會使用 Git 與 API。

| 階段 | 時間 | 課程 | 連結 |
|---|---|---|---|
| 1. LLM 基本認識 | 第 1–2 週 | Generative AI for Everyone（快速看完）+ Karpathy「Intro to LLMs」或 3Blue1Brown Transformer 影片 | [01](../courses/01-ai-literacy.md)、[02](../courses/02-ml-foundations.md) |
| 2. 提示工程 | 第 2–3 週 | DeepLearning.AI 提示工程短課 → Anthropic 互動式提示教學 | [05](../courses/05-generative-ai-apps.md) |
| 3. 應用開發全景 | 第 3–7 週 | 微軟 Generative AI for Beginners（21 課） | [05](../courses/05-generative-ai-apps.md) |
| 4. RAG 深入 | 第 7–10 週 | DeepLearning.AI RAG 課程 或 LLM Zoomcamp | [05](../courses/05-generative-ai-apps.md)、[09](../courses/09-mlops-llmops.md) |
| 5. 評估與上線 | 第 10–14 週 | LLM Zoomcamp 評估與監控模組 + 原廠平台課程（Anthropic／OpenAI／Google／Azure 擇一） | [09](../courses/09-mlops-llmops.md) |
| 6. 補原理（並行） | 全程 | Google MLCC 或 Karpathy「從零打造 GPT」 | [02](../courses/02-ml-foundations.md)、[03](../courses/03-deep-learning.md) |

**里程碑專案**：打造一個針對特定領域文件（如公司內規、產品手冊）的 RAG 問答系統，包含：
- 至少 50 題的評估資料集與自動化評估
- 引用來源標示
- 部署成可公開存取的網頁應用
- 一份記錄失敗案例與改進過程的技術文章

**可選認證**：AWS Generative AI Developer – Professional、Azure AI-103、NVIDIA NCA-GENL。

---

## 路線 C：AI 代理工程師

**目標**：設計、建構與評估能自主規劃、使用工具、完成多步驟任務的代理系統。

**先備條件**：完成路線 B 的第 1–3 階段，或有同等經驗。

| 階段 | 時間 | 課程 | 連結 |
|---|---|---|---|
| 1. 代理設計模式 | 第 1–2 週 | 吳恩達 Agentic AI | [06](../courses/06-ai-agents.md) |
| 2. 框架實作 | 第 3–5 週 | Hugging Face AI Agents Course（含期末排行榜專案） | [06](../courses/06-ai-agents.md) |
| 3. MCP | 第 5–6 週 | Anthropic MCP 入門 → Hugging Face MCP Course | [06](../courses/06-ai-agents.md) |
| 4. 系統化與上線 | 第 6–8 週 | 微軟 AI Agents for Beginners（記憶、上下文工程、安全、部署章節）或 Kaggle 5 天代理密集課 | [06](../courses/06-ai-agents.md) |
| 5. 前沿與研究 | 第 8–10 週 | 柏克萊 Agentic AI MOOC 精選講座 | [06](../courses/06-ai-agents.md) |
| 6. AI 程式代理（選修） | 隨時 | Claude Code in Action、AI Dev Tools Zoomcamp | [06](../courses/06-ai-agents.md) |

**里程碑專案**：打造一個能完成真實任務的代理（如自動研究報告、程式碼審查、客服工單處理），需包含：
- 自建的 MCP 伺服器（連接至少一個真實資料來源或 API）
- 執行軌跡記錄（Trace）與錯誤分析
- 至少 30 個測試任務的評估結果，並比較不同設計（如有無反思、單代理 vs 多代理）的成功率與成本

---

## 路線 D：機器學習／深度學習扎根

**目標**：從數學與原理層面理解機器學習與深度學習，能自行實作與除錯模型。

**先備條件**：Python 程式能力、高中數學。

| 階段 | 時間 | 課程 | 連結 |
|---|---|---|---|
| 1. 數學直覺 | 第 1–4 週 | 3Blue1Brown 線性代數、微積分 + DeepLearning.AI 數學專項（或 MIT 18.06 選讀） | [02](../courses/02-ml-foundations.md) |
| 2. 機器學習 | 第 5–12 週 | 吳恩達 ML Specialization 或 Google MLCC + 哈佛 CS50 AI | [02](../courses/02-ml-foundations.md) |
| 3. 實作練習 | 第 10–14 週 | Kaggle Learn 系列 + 參加 1 場 Kaggle 入門競賽 | [02](../courses/02-ml-foundations.md) |
| 4. 深度學習 | 第 13–24 週 | 吳恩達 Deep Learning Specialization 或 fast.ai；搭配《Understanding Deep Learning》 | [03](../courses/03-deep-learning.md) |
| 5. 從零手刻 | 第 20–30 週 | Karpathy Neural Networks: Zero to Hero（全部跟著寫一遍） | [03](../courses/03-deep-learning.md) |
| 6. 專項選修 | 第 30 週以後 | 電腦視覺（CS231n）、NLP（CS224N）、強化學習（HF Deep RL）擇一深入 | [07](../courses/07-vision-multimodal.md)、[04](../courses/04-nlp-llm.md)、[08](../courses/08-reinforcement-learning.md) |

**里程碑專案**：
1. 不使用任何高階框架，以 NumPy 從零實作多層神經網路並在 MNIST 上訓練
2. 用 PyTorch 完成一個 Kaggle 競賽，並撰寫完整的實驗紀錄
3. 跟著 Karpathy 重現一個小型 GPT，並在自己的資料（如中文文本）上訓練

---

## 路線 E：LLM 研究與模型訓練

**目標**：理解並能實作 LLM 的完整訓練流程（預訓練、微調、對齊、推論最佳化），具備進入模型訓練團隊或研究所的能力。

**先備條件**：完成路線 D 或有同等基礎；熟練 PyTorch。

| 階段 | 時間 | 課程 | 連結 |
|---|---|---|---|
| 1. NLP 理論 | 第 1–10 週 | 史丹佛 CS224N（含作業） | [04](../courses/04-nlp-llm.md) |
| 2. 從零打造 LLM | 第 6–14 週 | Raschka《LLMs from Scratch》或 Datawhale Happy-LLM | [04](../courses/04-nlp-llm.md) |
| 3. 開源生態系 | 第 10–16 週 | Hugging Face LLM Course（含推理模型章節）+ smol course | [04](../courses/04-nlp-llm.md) |
| 4. 完整堆疊 | 第 16–30 週 | 史丹佛 CS336（全部作業）+ nanochat | [04](../courses/04-nlp-llm.md) |
| 5. 系統與效能 | 第 24 週以後 | CMU Deep Learning Systems、GPU MODE 講座 | [09](../courses/09-mlops-llmops.md) |
| 6. 強化學習與對齊 | 第 24 週以後 | 阿爾伯塔 RL 專項或 HF Deep RL → ARENA（可解釋性與評估） | [08](../courses/08-reinforcement-learning.md)、[10](../courses/10-ai-safety-ethics.md) |
| 7. 追蹤前沿 | 持續 | CS25 講座、李宏毅最新課程、閱讀論文 | [04](../courses/04-nlp-llm.md)、[11](../courses/11-chinese-resources.md) |

**里程碑專案**：
1. 從零預訓練一個小型語言模型（數千萬參數級），並記錄規模法則實驗
2. 對開源模型進行 SFT + DPO／GRPO，並在公開基準上比較前後差異
3. 實作一個 GPU 核心（如以 Triton 實作 FlashAttention）並做效能分析

---

## 路線 F：MLOps／LLMOps 工程師

**目標**：建立可靠的 ML／LLM 系統基礎設施：資料管線、實驗追蹤、部署、監控與評估。

**先備條件**：後端或 DevOps 經驗（Docker、CI/CD、雲端服務）。

| 階段 | 時間 | 課程 | 連結 |
|---|---|---|---|
| 1. ML 基本觀念 | 第 1–3 週 | Google MLCC | [02](../courses/02-ml-foundations.md) |
| 2. ML 專案生命週期 | 第 3–5 週 | 吳恩達 Machine Learning in Production | [09](../courses/09-mlops-llmops.md) |
| 3. MLOps 實作 | 第 5–10 週 | MLOps Zoomcamp 或 Made With ML | [09](../courses/09-mlops-llmops.md) |
| 4. LLMOps | 第 10–14 週 | LLM Zoomcamp + Full Stack Deep Learning LLM Bootcamp 講座 | [09](../courses/09-mlops-llmops.md) |
| 5. 推論與部署 | 第 14–16 週 | NVIDIA DLI 部署課程（如 NIM） | [09](../courses/09-mlops-llmops.md) |
| 6. 系統設計 | 持續 | CS329S 教材 + Chip Huyen《AI Engineering》 | [09](../courses/09-mlops-llmops.md) |

**里程碑專案**：建立一條完整的 LLM 應用管線：版本化的提示與評估資料集、CI 中的自動評估、灰度發布、成本與延遲監控儀表板、使用者回饋收集。

**可選認證**：AWS ML Engineer – Associate、Google Cloud Professional ML Engineer、Azure AI-103。

---

## 路線 G：全中文學習路線

**目標**：以中文資源為主，完成從零基礎到 LLM 應用與代理開發的學習。

| 階段 | 時間 | 課程 | 連結 |
|---|---|---|---|
| 1. 通識入門 | 第 1–3 週 | 李宏毅「生成式人工智慧導論 2024」 | [11](../courses/11-chinese-resources.md) |
| 2. 數學直覺 | 第 3–5 週 | 3Blue1Brown 中文頻道（線性代數、神經網路系列） | [11](../courses/11-chinese-resources.md) |
| 3. 機器學習 | 第 5–14 週 | 李宏毅「機器學習」（2021–2023）；重理論者加修林軒田「機器學習基石」 | [11](../courses/11-chinese-resources.md) |
| 4. 深度學習 | 第 12–24 週 | 李沐《動手學深度學習》+ B 站配套課程 | [11](../courses/11-chinese-resources.md) |
| 5. 大型語言模型 | 第 24–32 週 | 李宏毅「生成式 AI 時代下的機器學習 2025」→ Datawhale Happy-LLM | [11](../courses/11-chinese-resources.md) |
| 6. 應用開發 | 第 30–36 週 | Datawhale llm-cookbook → Self-LLM；微軟 Generative AI for Beginners（中文翻譯版） | [11](../courses/11-chinese-resources.md)、[05](../courses/05-generative-ai-apps.md) |
| 7. 代理開發 | 第 36–44 週 | Datawhale Hello-Agents；微軟 AI Agents for Beginners（中文翻譯版） | [11](../courses/11-chinese-resources.md)、[06](../courses/06-ai-agents.md) |
| 8. 銜接英文前沿 | 持續 | 李沐「論文精讀」→ 逐步改讀英文課程與論文 | [11](../courses/11-chinese-resources.md) |

**里程碑專案**：以中文資料打造一個 RAG 問答系統或代理應用，並撰寫中文技術文章分享學習歷程。

---

## 通用學習建議

1. **一次只上一門主課**，搭配一個實作專案；完成後再開始下一門。
2. **每學完一個階段，就做一個可以展示的作品**，放到 GitHub 並寫 README。
3. **加入學習社群**：Hugging Face Discord、DataTalksClub Slack、DeepLearning.AI 論壇、Datawhale 社群等，有問題時更容易得到幫助。
4. **建立「學習日誌」**：記錄每週學了什麼、卡在哪裡、怎麼解決。這也是很好的技術寫作素材。
5. **定期回顧本倉庫的[分析報告](analysis.md)**，留意新課程與趨勢變化。
