# AI 中英術語對照表

> 收錄 AI 課程中最常出現的術語，方便在中文與英文教材之間切換。
> 「台灣常用」與「中國大陸常用」譯名不同時，兩者並列（台灣／大陸）。

[← 回到總覽](../README.md)

## 基礎概念

| 英文 | 中文 | 說明 |
|---|---|---|
| Artificial Intelligence (AI) | 人工智慧／人工智能 | 讓機器展現類似人類智慧行為的技術總稱 |
| Machine Learning (ML) | 機器學習 | 讓電腦從資料中學習規律，而非依賴明確寫好的規則 |
| Deep Learning (DL) | 深度學習 | 使用多層神經網路的機器學習方法 |
| Neural Network | 神經網路／神經網絡 | 由大量相連的「神經元」組成的計算模型 |
| Supervised Learning | 監督式學習／監督學習 | 從有標註答案的資料中學習 |
| Unsupervised Learning | 非監督式學習／無監督學習 | 從沒有標註的資料中找出結構 |
| Self-supervised Learning | 自監督學習 | 從資料本身自動產生學習目標（LLM 預訓練即屬此類） |
| Reinforcement Learning (RL) | 強化學習 | 透過試誤與獎勵訊號學習決策 |
| Generative AI | 生成式 AI | 能產生文字、影像、聲音等新內容的 AI |
| Discriminative Model | 鑑別式模型／判別式模型 | 學習分類或預測標籤的模型 |
| Training / Inference | 訓練／推論（推理） | 學習模型參數的過程／使用模型產生輸出的過程 |
| Dataset | 資料集／數據集 | 用來訓練或評估模型的資料 |
| Feature | 特徵 | 描述資料的屬性 |
| Label | 標籤 | 監督式學習中的正確答案 |

## 模型訓練

| 英文 | 中文 | 說明 |
|---|---|---|
| Loss Function | 損失函數 | 衡量模型預測與正確答案差距的函數 |
| Gradient Descent | 梯度下降 | 沿著損失函數下降最快的方向更新參數 |
| Backpropagation | 反向傳播 | 計算神經網路中每個參數梯度的演算法 |
| Overfitting / Underfitting | 過擬合／欠擬合 | 模型過度記憶訓練資料／學得不夠 |
| Regularization | 正則化 | 防止過擬合的技術 |
| Hyperparameter | 超參數 | 訓練前需人為設定的參數（如學習率） |
| Epoch / Batch | 訓練輪次／批次 | 完整看過一次資料集／每次更新使用的資料量 |
| Embedding | 嵌入（向量）／嵌入 | 將文字、影像等轉換為向量表示 |
| Convolutional Neural Network (CNN) | 卷積神經網路 | 擅長處理影像的網路架構 |
| Recurrent Neural Network (RNN) | 循環神經網路 | 處理序列資料的網路架構 |
| Attention Mechanism | 注意力機制 | 讓模型動態聚焦於輸入中相關部分的機制 |
| Transformer | Transformer | 以自注意力為核心的架構，是現代 LLM 的基礎 |
| Scaling Laws | 規模法則／縮放定律 | 模型表現隨參數量、資料量、算力增加的規律 |

## 大型語言模型（LLM）

| 英文 | 中文 | 說明 |
|---|---|---|
| Large Language Model (LLM) | 大型語言模型／大語言模型 | 以大量文字訓練、能理解與生成語言的模型 |
| Token / Tokenizer | 詞元（Token）／分詞器 | 模型處理文字的最小單位／將文字切成 Token 的工具 |
| Pre-training | 預訓練 | 在大量資料上學習通用能力的階段 |
| Post-training | 後訓練 | 預訓練後的微調、對齊與強化學習等階段 |
| Fine-tuning | 微調 | 在特定資料上繼續訓練以適應特定任務 |
| Supervised Fine-Tuning (SFT) | 監督式微調 | 以「指令-回答」範例進行微調 |
| Parameter-Efficient Fine-Tuning (PEFT) | 參數高效微調 | 只更新少量參數的微調方法 |
| LoRA (Low-Rank Adaptation) | 低秩適應 | 最常見的參數高效微調方法 |
| Alignment | 對齊 | 讓模型行為符合人類意圖與價值觀 |
| RLHF | 基於人類回饋的強化學習 | 以人類偏好資料訓練獎勵模型，再以強化學習優化 |
| DPO (Direct Preference Optimization) | 直接偏好最佳化 | 不需獎勵模型的偏好對齊方法 |
| GRPO (Group Relative Policy Optimization) | 群組相對策略最佳化 | 常用於訓練推理模型的強化學習演算法 |
| RLVR | 可驗證獎勵的強化學習 | 以可自動驗證的答案（如數學、程式）作為獎勵 |
| Reasoning Model | 推理模型 | 會先產生思考過程再作答的 LLM |
| Context Window | 上下文視窗／上下文窗口 | 模型一次能處理的 Token 數上限 |
| Hallucination | 幻覺 | 模型產生看似合理但錯誤的內容 |
| Quantization | 量化 | 降低模型數值精度以節省記憶體與加速推論 |
| Distillation | 蒸餾 | 以大模型教導小模型 |
| Mixture of Experts (MoE) | 混合專家模型 | 每次只啟用部分參數的模型架構 |
| Multimodal | 多模態 | 能同時處理文字、影像、聲音等多種資料 |

## 應用開發

| 英文 | 中文 | 說明 |
|---|---|---|
| Prompt / Prompt Engineering | 提示／提示工程 | 給模型的輸入指令／設計有效提示的方法 |
| System Prompt | 系統提示 | 設定模型角色與行為規則的提示 |
| Few-shot / Zero-shot | 少樣本／零樣本 | 提示中給予少量範例／不給範例 |
| Chain of Thought (CoT) | 思維鏈 | 引導模型逐步推理 |
| Retrieval-Augmented Generation (RAG) | 檢索增強生成 | 先檢索相關資料再讓模型生成回答 |
| Vector Database | 向量資料庫／向量數據庫 | 儲存與搜尋嵌入向量的資料庫 |
| Chunking | 分塊 | 將長文件切成適合檢索的片段 |
| Reranking | 重新排序／重排序 | 對檢索結果再次排序以提升相關性 |
| Function Calling / Tool Use | 函式呼叫／工具使用（函數調用） | 讓模型呼叫外部函式或 API |
| Structured Output | 結構化輸出 | 讓模型輸出符合指定格式（如 JSON） |
| Evaluation (Evals) | 評估 | 系統化衡量模型或應用的表現 |
| LLM-as-a-Judge | LLM 作為評審 | 使用 LLM 評估其他模型的輸出 |
| Guardrails | 防護機制／護欄 | 限制模型輸入輸出以確保安全 |

## AI 代理

| 英文 | 中文 | 說明 |
|---|---|---|
| AI Agent | AI 代理／智能體 | 能自主規劃、使用工具並完成多步驟任務的 AI 系統 |
| Agentic AI / Agentic Workflow | 代理式 AI／代理式工作流程 | 以代理方式運作的 AI 系統或流程 |
| Reflection | 反思 | 代理檢查並改進自己輸出的設計模式 |
| Planning | 規劃 | 代理將任務拆解為步驟的設計模式 |
| Multi-agent System | 多代理系統／多智能體系統 | 多個代理分工協作的系統 |
| Model Context Protocol (MCP) | 模型上下文協定／模型上下文協議 | 讓 AI 應用連接外部工具與資料的開放標準 |
| Context Engineering | 上下文工程 | 設計與管理提供給模型的上下文資訊 |
| Agent Skills | 代理技能 | 可重複使用、封裝好的代理能力模組 |
| Memory | 記憶 | 代理保存與取用過往資訊的機制 |
| Trace / Observability | 執行軌跡／可觀測性 | 記錄代理每一步的行為以便除錯 |
| Human-in-the-loop | 人機協作／人在迴路 | 在關鍵步驟加入人類確認 |
| Coding Agent | 程式代理／編程智能體 | 能讀寫程式碼、執行指令的 AI 代理 |
| Vibe Coding | 氛圍程式設計（Vibe Coding） | 主要以自然語言指揮 AI 撰寫程式的開發方式 |

## 系統與部署

| 英文 | 中文 | 說明 |
|---|---|---|
| MLOps / LLMOps | 機器學習維運／大模型維運 | 將 ML／LLM 系統可靠上線與維運的實務 |
| Experiment Tracking | 實驗追蹤 | 記錄訓練參數與結果 |
| Model Registry | 模型註冊庫 | 管理模型版本的系統 |
| Data Drift / Concept Drift | 資料漂移／概念漂移 | 上線後資料分布或規律改變 |
| Latency / Throughput | 延遲／吞吐量 | 單次回應時間／單位時間處理量 |
| GPU / CUDA | 圖形處理器／CUDA | AI 訓練與推論的主要硬體／NVIDIA 的 GPU 程式平台 |
| Kernel | 核心（運算核心）／算子 | 在 GPU 上執行的底層運算程式 |
| Distributed Training | 分散式訓練／分布式訓練 | 使用多個 GPU 或機器共同訓練 |

## 電腦視覺與生成

| 英文 | 中文 | 說明 |
|---|---|---|
| Computer Vision (CV) | 電腦視覺／計算機視覺 | 讓電腦理解影像與影片 |
| Object Detection | 物件偵測／目標檢測 | 找出影像中物體的位置與類別 |
| Segmentation | 分割 | 逐像素標註影像區域 |
| Vision Transformer (ViT) | 視覺 Transformer | 將 Transformer 應用於影像 |
| Diffusion Model | 擴散模型 | 透過逐步去除雜訊來生成影像的模型 |
| Flow Matching | 流匹配 | 新一代生成模型的訓練方法 |
| GAN | 生成對抗網路 | 由生成器與判別器對抗訓練的模型 |
| CLIP | CLIP（對比語言-影像預訓練） | 將文字與影像對應到同一向量空間的模型 |
| ASR / TTS | 自動語音辨識／語音合成 | 語音轉文字／文字轉語音 |

## AI 安全與治理

| 英文 | 中文 | 說明 |
|---|---|---|
| AI Safety | AI 安全 | 確保 AI 系統不造成意外傷害的研究與實務 |
| Interpretability | 可解釋性 | 理解模型內部如何做出決策 |
| Mechanistic Interpretability | 機制可解釋性 | 從神經元與電路層級逆向工程模型 |
| Bias / Fairness | 偏誤／公平性 | 模型對特定群體的不公平表現 |
| Red Teaming | 紅隊測試 | 主動攻擊模型以找出弱點 |
| Jailbreak / Prompt Injection | 越獄／提示注入 | 誘使模型繞過限制／在輸入中夾帶惡意指令 |
| Responsible AI | 負責任 AI | 以倫理、安全、透明為原則開發與使用 AI |
| AI Governance | AI 治理 | 規範 AI 發展與使用的政策、法規與制度 |
| AI Literacy / AI Fluency | AI 素養／AI 流暢力 | 理解並有效、負責任地使用 AI 的能力 |
