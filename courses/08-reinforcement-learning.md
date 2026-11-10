# 08｜強化學習與機器人學習

> 適合對象：對決策、遊戲 AI、機器人控制，或 LLM 後訓練（RLHF、推理模型）有興趣的學習者。
> 趨勢：強化學習（Reinforcement Learning, RL）因「推理模型」與可驗證獎勵強化學習（RLVR）、GRPO 等 LLM 後訓練技術而重新成為熱門；機器人學習則隨開源工具（如 LeRobot）與「具身智慧（Embodied AI）」熱潮快速發展。

[← 回到總覽](../README.md)

## 速覽

| # | 課程（中文譯名／英文原名） | 提供者 | 程度 | 費用 | 重點 |
|---|---|---|---|---|---|
| 1 | Hugging Face 深度強化學習課程 / Deep RL Course | Hugging Face | ⭐⭐ | 免費（含證書） | 實作入門 |
| 2 | 強化學習專項課程 / Reinforcement Learning Specialization | 阿爾伯塔大學（Coursera） | ⭐⭐ | 部分免費 | 結構化理論 |
| 3 | David Silver 強化學習講座 / RL Lectures | UCL × DeepMind | ⭐⭐～⭐⭐⭐ | 免費 | 經典理論 |
| 4 | 《強化學習導論》教科書 / Reinforcement Learning: An Introduction | Sutton & Barto | ⭐⭐～⭐⭐⭐ | 免費電子書 | 領域聖經 |
| 5 | 史丹佛 CS234 強化學習 / CS234: Reinforcement Learning | 史丹佛大學 | ⭐⭐⭐ | 錄影免費 | 研究所課程 |
| 6 | 柏克萊 CS285 深度強化學習 / CS285: Deep RL | 加州大學柏克萊分校 | ⭐⭐⭐ | 錄影免費 | 深度 RL 與機器人 |
| 7 | OpenAI 深度強化學習入門 / Spinning Up in Deep RL | OpenAI | ⭐⭐～⭐⭐⭐ | 免費 | 經典教材（已停止維護） |
| 8 | Hugging Face 機器人課程 / Robotics Course | Hugging Face | ⭐⭐ | 免費 | LeRobot 實作 |

---

## 1. Hugging Face 深度強化學習課程（Deep Reinforcement Learning Course）

- **提供者**：Hugging Face
- **程度**：⭐⭐ 中級｜**費用**：免費，完成作業可取得證書
- **連結**：<https://huggingface.co/learn/deep-rl-course>

**簡介**：從零開始的實作型 RL 課程，讓你訓練代理玩遊戲（如月球登陸器、Atari、Unity 環境），並將模型上傳到 Hugging Face Hub 與他人比較。

**主題涵蓋**：Q-Learning、深度 Q 網路（DQN）、策略梯度、Actor-Critic、PPO、多代理強化學習，以及 RLHF 等延伸單元；使用 Stable-Baselines3、Unity ML-Agents 等工具。

**點評**：寓教於樂、門檻友善，是 RL 實作的最佳免費入門。

---

## 2. 強化學習專項課程（Reinforcement Learning Specialization）

- **提供者**：阿爾伯塔大學（University of Alberta）× Amii，Martha White、Adam White 主講
- **程度**：⭐⭐ 中級｜**費用**：Coursera 首個模組可免費預覽，完整內容與證書需付費（可申請助學金）｜**時長**：4 門課，約 4–6 個月
- **連結**：<https://www.coursera.org/specializations/reinforcement-learning>

**課程組成**：RL 基礎（MDP、動態規劃）、取樣式學習方法（蒙地卡羅、TD 學習）、函數近似預測與控制、完整 RL 系統（Capstone）。課程緊扣 Sutton & Barto 教科書。

**點評**：被許多人視為最有系統的結構化 RL 課程，理論與程式作業平衡良好。

---

## 3. David Silver 強化學習講座（UCL Course on RL）

- **提供者**：倫敦大學學院（UCL）× DeepMind，David Silver（AlphaGo 主要作者）
- **程度**：⭐⭐～⭐⭐⭐｜**費用**：免費（YouTube）｜**時長**：10 講
- **連結**：<https://www.davidsilver.uk/teaching/>

**簡介**：2015 年錄製的經典 RL 理論課：馬可夫決策過程、動態規劃、無模型預測與控制、函數近似、策略梯度、整合學習與規劃、探索與利用等。DeepMind 與 UCL 於 2021 年另有更新版系列講座可作補充。

**點評**：雖然年代較早，但講解清晰，至今仍是理解 RL 理論的最佳影片之一。

---

## 4. 《強化學習導論》（Reinforcement Learning: An Introduction, 2nd Edition）

- **提供者**：Richard S. Sutton、Andrew G. Barto（2024 年圖靈獎得主）
- **程度**：⭐⭐～⭐⭐⭐｜**費用**：作者官網提供免費電子版
- **連結**：<http://incompleteideas.net/book/the-book-2nd.html>

**點評**：RL 領域的「聖經」，搭配第 2、3 項課程閱讀效果最佳。

---

## 5. 史丹佛 CS234：強化學習（CS234: Reinforcement Learning）

- **提供者**：史丹佛大學，Emma Brunskill 教授
- **程度**：⭐⭐⭐ 進階｜**費用**：課程網站與錄影免費
- **連結**：<https://web.stanford.edu/class/cs234/>

**點評**：研究所等級、涵蓋面廣的 RL 課程，包含離線 RL、從人類回饋學習等較新主題。

---

## 6. 柏克萊 CS285：深度強化學習（CS285: Deep Reinforcement Learning）

- **提供者**：加州大學柏克萊分校，Sergey Levine 教授
- **程度**：⭐⭐⭐ 進階｜**費用**：錄影、投影片與作業免費
- **連結**：<https://rail.eecs.berkeley.edu/deeprlcourse/>

**簡介**：深度 RL 最完整的研究所課程之一，涵蓋模仿學習、策略梯度、Actor-Critic、基於價值的方法、基於模型的 RL、離線 RL、探索、逆強化學習，以及在機器人上的應用。

**點評**：想從事 RL 或機器人研究者的首選。數學與程式要求都高。

---

## 7. OpenAI 深度強化學習入門（Spinning Up in Deep RL）

- **提供者**：OpenAI
- **程度**：⭐⭐～⭐⭐⭐｜**費用**：免費
- **連結**：<https://spinningup.openai.com/>

**簡介**：2018 年發布的教材，包含 RL 核心概念介紹、關鍵論文清單與 VPG、PPO、DDPG、TD3、SAC 等演算法的簡潔實作。

**點評**：概念介紹與論文清單仍有參考價值，但程式碼已多年未維護，實作建議改用 Stable-Baselines3 或 CleanRL 等現代函式庫。

---

## 8. Hugging Face 機器人課程（Robotics Course）

- **提供者**：Hugging Face
- **程度**：⭐⭐ 中級｜**費用**：免費
- **連結**：<https://github.com/huggingface/robotics-course>

**簡介**：以 Hugging Face 的開源機器人學習函式庫 **LeRobot** 為核心，介紹機器人學習中的**模仿學習**與**強化學習**方法。課程由 LeRobot 團隊的「機器人學習教學（Robot Learning Tutorial）」改寫而成。

**進度**：依官方倉庫，課程簡介、機器人學導論與古典機器人學等單元已上線；強化學習、模仿學習與機器人基礎模型單元陸續釋出中。

**點評**：「具身智慧」入門的友善選擇，可搭配低成本的開源機械手臂實作。

---

## 本類別選課建議

| 你的目標 | 建議路線 |
|---|---|
| 想先玩出成果 | Hugging Face Deep RL Course |
| 想打好 RL 理論 | 阿爾伯塔 RL 專項 + Sutton & Barto 教科書（或 David Silver 講座） |
| 想做 LLM 後訓練（RLHF／GRPO） | 上述任一基礎 → Hugging Face LLM Course 推理模型章節 → CS336 後訓練作業（見 [04｜NLP 與 LLM](04-nlp-llm.md)） |
| 想做機器人 | Deep RL Course → CS285 → Hugging Face Robotics Course（LeRobot） |
| 偏好中文 | 李宏毅「機器學習」課程中的強化學習單元，見 [11｜中文原生課程](11-chinese-resources.md) |

---

## 延伸清單：更多強化學習與機器人課程（2026 年 11 月增補）

| 課程（中文／英文） | 提供者 | 程度 | 連結 | 說明 |
|---|---|---|---|---|
| 深度強化學習 / CS224R | 史丹佛（Chelsea Finn） | ⭐⭐⭐ | <https://cs224r.stanford.edu/> | 模仿學習、離線 RL、機器人應用；2025 春季錄影公開 |
| 強化學習講座系列（2021） | DeepMind × UCL | ⭐⭐⭐ | [YouTube](https://www.youtube.com/playlist?list=PLqYmG7hTraZDVH599EItlEWsUOsJbAodm) | David Silver 經典課的更新版 |
| 深度強化學習基礎 / Foundations of Deep RL | Pieter Abbeel | ⭐⭐ | [YouTube](https://www.youtube.com/playlist?list=PLwRJQ4m4UJjNymuBM9RdmB3Z9N5-0IlY0) | 6 講精華 |
| 實用強化學習 / Practical RL | Yandex School of Data Analysis | ⭐⭐⭐ | <https://github.com/yandexdataschool/Practical_RL> | 每週講座與實作 |
| 強化學習（2025 秋） | 多倫多大學 ECE1508 | ⭐⭐⭐ | <https://bereyhi-courses.github.io/rl-utoronto/lectures/> | 較新的完整錄影 |
| 強化學習（2024） | 華盛頓大學 CSE 579／542 | ⭐⭐⭐ | <https://courses.cs.washington.edu/courses/cse579/24au/schedule/> | 講義公開 |
| 強化學習的數學原理 | 趙世鈺（西湖大學） | ⭐⭐ | <https://github.com/MathFoundationRL/Book-Mathematical-Foundation-of-Reinforcement-Learning> | **中英文**；書＋影片，從貝爾曼方程一路推到 Actor-Critic，以清楚嚴謹著稱 |
| 動手學強化學習 | 上海交通大學（張偉楠等） | ⭐⭐ | <https://hrl.boyuai.com/> | **中文**；每章皆為可執行 Notebook |
| Easy RL（蘑菇書） | Datawhale | ⭐⭐ | <https://github.com/datawhalechina/easy-rl> | **中文**；整合李宏毅、周博磊、李科澆課程的教程 |
| 深度強化學習 | 王樹森 | ⭐⭐ | <https://github.com/wangshusen/DRL> | **中文**影片＋講義 |
| 機器人操作／欠驅動機器人學 | MIT（Russ Tedrake） | ⭐⭐⭐ | <https://manipulation.csail.mit.edu/> | 線上教科書＋影片＋Notebook |
| 機器人自主性原理 / Principles of Robot Autonomy | 史丹佛（Marco Pavone 等） | ⭐⭐⭐ | [史丹佛新聞](https://news.stanford.edu/stories/2026/10/autonomous-robotics-education-curriculum-textbook) | 2026 年 10 月公開：教科書免費線上閱讀，並附影片、投影片、開源程式與作業 |
| 進階機器人學 / CS287 | UC Berkeley（Pieter Abbeel） | ⭐⭐⭐ | <https://people.eecs.berkeley.edu/~pabbeel/cs287-fa19/> | 最佳控制、運動規劃、估測 |
| 現代機器人學 / Modern Robotics | 西北大學，Coursera | ⭐⭐ | <https://www.coursera.org/specializations/modernrobotics> | 部分免費；運動學、動力學與控制的基礎 |
| 人人都能學的具身智慧 / Every Embodied | Datawhale | ⭐⭐ | <https://github.com/datawhalechina/every-embodied> | **中文**；具身智慧入門 |
