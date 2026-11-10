# 04｜自然語言處理與大型語言模型（NLP & LLM）

> 適合對象：已具備深度學習基礎，想理解 Transformer 與大型語言模型（LLM）如何被設計、訓練、微調與對齊的人。
> 2025–2026 年最明顯的趨勢是「**從零打造 LLM**」類課程的興起：學習者不再滿足於呼叫 API，而是想親手走過分詞、預訓練、後訓練（Post-training）與強化學習的完整流程。

[← 回到總覽](../README.md)

## 速覽

| # | 課程（中文譯名／英文原名） | 提供者 | 程度 | 費用 | 重點 |
|---|---|---|---|---|---|
| 1 | 史丹佛 CS224N 深度學習自然語言處理 / CS224N: NLP with Deep Learning | 史丹佛大學 | ⭐⭐⭐ | 教材與錄影免費 | NLP 理論經典 |
| 2 | 史丹佛 CS336 從零打造語言模型 / CS336: Language Modeling from Scratch | 史丹佛大學 | ⭐⭐⭐ | 教材與錄影免費 | 完整 LLM 訓練堆疊 |
| 3 | 史丹佛 CS25 Transformer 聯盟 / CS25: Transformers United | 史丹佛大學 | ⭐⭐～⭐⭐⭐ | 錄影免費 | 前沿講座 |
| 4 | Hugging Face 大型語言模型課程 / LLM Course | Hugging Face | ⭐⭐ | 免費 | Transformers 生態系實作 |
| 5 | LLM 課程路線圖 / LLM Course (mlabonne) | Maxime Labonne | ⭐⭐～⭐⭐⭐ | 免費（GitHub） | 學習路線 + Colab |
| 6 | 從零打造大型語言模型 / Build a Large Language Model (From Scratch) | Sebastian Raschka | ⭐⭐ | 程式碼免費，書籍付費 | 用 PyTorch 手刻 GPT |
| 7 | nanochat 與 LLM101n | Andrej Karpathy | ⭐⭐⭐ | 免費 | 端到端類 ChatGPT |
| 8 | 大型語言模型的生成式 AI / Generative AI with LLMs | DeepLearning.AI × AWS | ⭐⭐ | 部分免費 | LLM 生命週期 |
| 9 | smol 微調課程 / smol course | Hugging Face | ⭐⭐ | 免費 | 小模型微調與對齊 |
| 10 | DeepLearning.AI LLM 原理短課 | DeepLearning.AI | ⭐⭐ | 免費 | 1–2 小時主題短課 |

---

## 1. 史丹佛 CS224N：深度學習自然語言處理（CS224N: Natural Language Processing with Deep Learning）

- **提供者**：史丹佛大學 NLP 團隊（Christopher Manning 等）
- **程度**：⭐⭐⭐ 進階｜**費用**：投影片、作業、程式碼與歷年錄影免費；史丹佛線上另有付費的 XCS224N 專業版（含評分與輔導）
- **連結**：<https://web.stanford.edu/class/cs224n/>

**簡介**：全球最知名的 NLP 課程，2026 年冬季學期仍持續開設。從詞向量一路講到 Transformer、預訓練模型、提示與 RLHF。

**你會學到**：詞向量（word2vec、GloVe）、相依句法分析、RNN 與 LSTM、機器翻譯、注意力機制、Transformer、預訓練（BERT、GPT 系列）、後訓練與對齊、模型評估與倫理。

**點評**：打好 NLP 理論基礎的首選。作業需要大量 PyTorch 實作，建議預留完整的學期時間。公開版沒有評分與助教支援。

---

## 2. 史丹佛 CS336：從零打造語言模型（CS336: Language Modeling from Scratch）

- **提供者**：史丹佛大學，Percy Liang、Tatsunori Hashimoto
- **程度**：⭐⭐⭐ 進階（作業量極大）｜**費用**：講義、作業與錄影公開免費
- **連結**：<https://cs336.stanford.edu/>

**簡介**：2025 年春季首開、2026 年春季再開的話題課程，讓學生**親手打造語言模型的完整技術堆疊**。2026 春季版講座錄影自 4 月起陸續公開於 YouTube（Stanford Online）。

**主題涵蓋**：
- 分詞（BPE Tokenizer）與 Transformer 實作
- GPU 核心（Kernels）、Triton、平行訓練等系統面議題
- 規模法則（Scaling Laws）
- 資料蒐集與清理
- 推論（Inference）最佳化
- 後訓練（Post-training）、可驗證獎勵的強化學習（RLVR）與推理能力

**點評**：目前最完整、最硬核的公開 LLM 課程，是想進入模型訓練或研究工作的人的「試金石」。需要扎實的 PyTorch、深度學習與系統基礎，部分作業需要 GPU 資源。

---

## 3. 史丹佛 CS25：Transformer 聯盟（CS25: Transformers United）

- **提供者**：史丹佛大學
- **程度**：⭐⭐～⭐⭐⭐｜**費用**：錄影免費（YouTube）
- **連結**：<https://web.stanford.edu/class/cs25/>

**簡介**：講座型課程，每季邀請 OpenAI、Google DeepMind、Anthropic、Meta 等機構與頂尖學者分享 Transformer 與 LLM 的最新研究。

**點評**：適合已有基礎、想追蹤前沿發展的人，可挑感興趣的講座觀看。

---

## 4. Hugging Face 大型語言模型課程（LLM Course）

- **提供者**：Hugging Face
- **程度**：⭐⭐ 中級｜**費用**：免費（各章節可取得證書）｜**時長**：12 章，自訂進度
- **連結**：<https://huggingface.co/learn/llm-course>

**簡介**：前身為 Hugging Face NLP Course，改版後聚焦 LLM。以 Transformers、Datasets、Tokenizers、Accelerate 等 Hugging Face 生態系工具為主。

**你會學到**：Transformer 模型的使用與微調、資料集處理、分詞器、建立 Gradio 示範、分享模型到 Hub、資料整理（Curation），以及**推理模型（Reasoning Models）與 GRPO 強化學習**等新章節。

**先備條件**：良好的 Python 能力，建議先上過深度學習入門課。部分章節有社群簡體中文翻譯。

**點評**：學習「業界實際怎麼用開源模型」的最佳官方教材，內容隨生態系持續更新。

---

## 5. LLM 課程路線圖（LLM Course by Maxime Labonne）

- **提供者**：Maxime Labonne（Liquid AI）
- **程度**：⭐⭐～⭐⭐⭐｜**費用**：免費開源（MIT 授權）
- **連結**：<https://github.com/mlabonne/llm-course>

**簡介**：GitHub 上最受歡迎的 LLM 學習路線之一（數萬顆星），分為三條路線：

| 路線 | 內容 |
|---|---|
| LLM 基礎（選修） | 數學、Python、神經網路 |
| LLM 科學家（LLM Scientist） | 架構、預訓練、監督式微調、偏好對齊（DPO、GRPO）、評估、量化 |
| LLM 工程師（LLM Engineer） | 執行 LLM、向量資料庫、RAG、代理、推論最佳化、部署、安全 |

**點評**：與其說是課程，更像是一份精心整理的「學習地圖 + 實作 Notebook」，搭配 Unsloth、Axolotl、MergeKit、llama.cpp 等工具。適合想自行規劃 LLM 學習路徑的人。

---

## 6. 從零打造大型語言模型（Build a Large Language Model (From Scratch)）

- **提供者**：Sebastian Raschka
- **程度**：⭐⭐ 中級｜**費用**：GitHub 程式碼與部分影片免費；書籍（Manning 出版）付費
- **連結**：<https://github.com/rasbt/LLMs-from-scratch>

**簡介**：以 PyTorch 從零實作類 GPT 模型：文字資料處理、注意力機制、GPT 架構、預訓練、分類微調與指令微調。GitHub 倉庫持續新增額外章節（例如新一代開源模型架構的從零實作）。

**點評**：比 CS336 更平易近人、比 Karpathy 影片更有書本結構，是「從零理解 LLM」的優秀中階選擇。

---

## 7. nanochat 與 LLM101n

- **提供者**：Andrej Karpathy（Eureka Labs）
- **程度**：⭐⭐⭐ 進階｜**費用**：免費開源
- **連結**：<https://github.com/karpathy/nanochat>

**簡介**：nanochat 於 2025 年 10 月發布，是一個約 8,000 行、極簡且完整的類 ChatGPT 訓練與部署流程：分詞器訓練、預訓練、中期訓練、監督式微調、強化學習、推論與網頁聊天介面。據報導，在 8×H100 節點上約 4 小時、約 100 美元即可完成基本訓練。

nanochat 被定位為 Karpathy 籌備中的課程 **LLM101n** 的結業專案。LLM101n 的[公開課綱](https://github.com/karpathy/LLM101n)規劃了 17 章（從 Bigram、Micrograd、注意力、Transformer、分詞、最佳化，到推論加速、SFT 與 RL 微調、部署與多模態），但倉庫註明課程尚未推出並已封存。

**點評**：適合已看完 Zero to Hero、想親自跑一次完整 LLM 訓練流程的人。

---

## 8. 大型語言模型的生成式 AI（Generative AI with Large Language Models）

- **提供者**：DeepLearning.AI × AWS
- **程度**：⭐⭐ 中級｜**費用**：Coursera 首個模組可免費預覽，完整內容與證書需付費（可申請助學金）｜**時長**：約 3 週（約 16 小時）
- **連結**：<https://www.coursera.org/learn/generative-ai-with-llms>

**簡介**：介紹 LLM 專案的完整生命週期：選模型、預訓練與規模法則、指令微調、參數高效微調（PEFT/LoRA）、RLHF，以及部署考量。

**點評**：結構清楚、適合工程師快速建立 LLM 全景概念。內容成形於 2023 年，部分技術（如 RLHF 細節、推理模型）已有更新的發展。

---

## 9. smol 微調課程（smol course）

- **提供者**：Hugging Face
- **程度**：⭐⭐ 中級｜**費用**：免費（可取得證書）｜**時長**：每週約 4 小時
- **連結**：<https://github.com/huggingface/smol-course>

**簡介**：聚焦**模型後訓練（Post-training）**的實作課程，使用小型模型（如 30 億參數的 SmolLM3）與 TRL 函式庫，學習監督式微調（SFT）與偏好對齊（如 DPO）。

**第二版單元**：指令微調 → 評估 → 偏好對齊（DPO）→ 視覺語言模型 → 強化學習 → 合成資料；課程採同儕審閱並設有排行榜。

**點評**：小模型可在消費級或免費雲端 GPU 上實作，是入門微調的實惠選擇。

---

## 10. DeepLearning.AI LLM 原理相關短課

- **提供者**：DeepLearning.AI 與合作夥伴
- **程度**：⭐⭐｜**費用**：影片可免費觀看（評分作業與證書等功能需 DeepLearning.AI Pro 訂閱）｜**時長**：每門約 1–2 小時
- **連結**：<https://www.deeplearning.ai/short-courses/>

**推薦主題範例**：
- Transformer LLM 如何運作（How Transformer LLMs Work）
- LLM 的後訓練（Post-training of LLMs）
- 以強化學習微調 LLM（如 GRPO 相關主題）

**點評**：短課是快速掌握單一主題的高效率方式，DeepLearning.AI 幾乎每月推出新短課，建議定期瀏覽目錄。

---

## 本類別選課建議

| 你的目標 | 建議路線 |
|---|---|
| 理解 LLM 原理（工程師） | Karpathy「從零打造 GPT」→ Raschka《LLMs from Scratch》→ Hugging Face LLM Course |
| 學會微調開源模型 | Hugging Face LLM Course → smol course → mlabonne 路線圖（LLM Scientist） |
| 進入模型訓練／研究 | CS224N → CS336（含作業）→ nanochat |
| 主管或 PM 想懂技術全景 | Generative AI with LLMs + CS25 精選講座 |
| 偏好中文 | 李宏毅「生成式 AI 導論」系列、Datawhale《Happy-LLM》，見 [11｜中文原生課程](11-chinese-resources.md) |

---

## 延伸清單：更多 NLP 與 LLM 課程（2026 年 11 月增補）

### 大學課程

| 課程（中文／英文） | 提供者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| Transformer 與大型語言模型 / CME295 | 史丹佛（Amidi 兄弟） | ⭐⭐ | [YouTube](https://www.youtube.com/playlist?list=PLoROMvodv4rObv1FMizXqumgVVdzX4_05)・[速查表](https://github.com/afshinea/stanford-cme-295-transformers-large-language-models) | 2025 秋季完整錄影；比 CS336 平易近人，適合作為銜接 |
| 進階自然語言處理 / CMU 11-711 | CMU | ⭐⭐⭐ | <https://cmu-l3.github.io/anlp-spring2025/> | 影片、講義與作業公開；另有 [2024 秋季版](https://www.phontron.com/class/anlp-fall2024/) |
| 大型語言模型：方法與應用 / CMU 11-667 | CMU | ⭐⭐⭐ | <https://cmu-llms.org/> | 六次作業涵蓋預訓練資料到 RAG |
| 大型語言模型系統 / CMU 11-868 | CMU | ⭐⭐⭐ | <https://llmsystem.github.io/llmsystem2025spring/> | LLM 的訓練與推論系統 |
| 生成式 AI / CMU 10-423／623 | CMU | ⭐⭐⭐ | <https://www.cs.cmu.edu/~mgormley/courses/10423/> | LLM 與影像生成並重 |
| 自然語言理解 / CS224U | 史丹佛 | ⭐⭐⭐ | <https://web.stanford.edu/class/cs224u/> | 評估方法與研究專題導向 |
| 理解大型語言模型 / COS 597G | 普林斯頓（陳丹琦） | ⭐⭐⭐ | <https://www.cs.princeton.edu/courses/archive/fall22/cos597G/> | 論文研討課的經典書單 |
| 進階自然語言處理 / CS685 | 麻州大學（Mohit Iyyer） | ⭐⭐⭐ | <https://people.cs.umass.edu/~miyyer/cs685/> | 完整錄影 |
| 基礎模型近期進展 / CS886 | 滑鐵盧大學 | ⭐⭐⭐ | <https://cs.uwaterloo.ca/~wenhuche/teaching/cs886/> | 涵蓋多模態與擴散模型 |
| 理解大型語言模型：基礎與安全 / CS194／294-267 | UC Berkeley | ⭐⭐⭐ | [YouTube](https://www.youtube.com/playlist?list=PLJ66BAXN6D8H_gRQJGjmbnS5qCWoxJNfe) | 2024 春季 |
| LLM 的可解釋性 / CS 6966 | 猶他大學 | ⭐⭐⭐ | <https://utah-llm-interpretability.notion.site/s26> | 2026 春季 |
| 自然語言處理（線上碩士版） | UT Austin（Greg Durrett） | ⭐⭐⭐ | <https://www.cs.utexas.edu/~gdurrett/courses/online-course/materials.html> | 短影片單元 |

### 企業與社群課程

| 課程（中文／英文） | 提供者 | 程度 | 費用 | 連結 | 說明 |
|---|---|---|---|---|---|
| AI 研究基礎 / AI Research Foundations | Google DeepMind × 倫敦大學學院（Google Skills） | ⭐⭐ | 免費（實驗室有每月額度） | <https://www.skills.google/collections/deepmind> | 8 門課：打造小型語言模型 → 表徵語言資料 → 設計與訓練神經網路 → Transformer → 微調 → 對齊 → 加速 → 結業專案；[實驗程式碼開源](https://github.com/google-deepmind/ai-foundations) |
| LLM 大學 / LLM University（LLMU） | Cohere | ⭐～⭐⭐ | 免費 | <https://cohere.com/llmu> | 嵌入、語意搜尋、RAG 的圖解課程 |
| NLP 課程 / NLP Course | Yandex School of Data Analysis | ⭐⭐⭐ | 免費 | <https://github.com/yandexdataschool/nlp_course> | 每週講座＋研討＋作業 |
| 為你而寫的 NLP 課程 / NLP Course For You | Lena Voita | ⭐⭐ | 免費 | <https://lena-voita.github.io/nlp_course.html> | 互動式圖解教材 |
| nanoGPT／minBPE／build-nanogpt | Andrej Karpathy | ⭐⭐⭐ | 免費 | <https://github.com/karpathy/build-nanogpt> | 搭配影片從空白檔案重現 GPT-2 |
| MiniMind | jingyaogong | ⭐⭐ | 免費 | <https://github.com/jingyaogong/minimind> | **中文**；約 2 小時、極低成本從零訓練一個 64M 參數的小語言模型，涵蓋預訓練、SFT、LoRA、DPO、PPO／GRPO、工具使用與蒸餾 |
| 從零打造推理模型 / Build a Reasoning Model (From Scratch) | Sebastian Raschka | ⭐⭐～⭐⭐⭐ | 程式碼免費 | <https://github.com/rasbt/reasoning-from-scratch> | 《LLMs from Scratch》續作 |
| LLM 評估指南 / LLM Evaluation Guidebook | Hugging Face | ⭐⭐ | 免費 | <https://github.com/huggingface/evaluation-guidebook> | 自動指標、人工評估、LLM 評審的實務 |
| Awesome-LLM | 社群 | — | 免費 | <https://github.com/Hannibal046/Awesome-LLM> | LLM 論文、課程與工具總表 |

中文 LLM 教材（《大語言模型》《大模型基礎》、Happy-LLM、清華大模型公開課等）見 [11｜中文原生課程](11-chinese-resources.md)；LLM 系統與效能見 [09](09-mlops-llmops.md)。
