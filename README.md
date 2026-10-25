# 學測英文滿級分神盾備考系統 (CEEC English Mastery Platform)

> 🚀 **專為「高二上學期學生」量身定制的 90 天極速掌握計畫**  
> 全面整合大考中心（CEEC）106~115 歷屆試題大數據、艾賓浩斯間隔重複（Leitner 5-Box）演算法、1,500 組滿級分核心搭配詞典與作文高分鷹架。

---

## 🌟 核心特色 (Core Features)

1. **大考中心命題大數據全拆解**
   - **0% 答案重複率**：歷屆 125 題正解單字 100% 不重複，真正循環的是「誘答干擾項」。
   - **84.8% 搭配詞原則**：詞彙題絕非盲目死背中文，而是透過前後文 2~3 個字鎖定慣用搭配（Collocation）。
   - **3:3:3:1 嚴格詞性配比**：每回 10 題精確分配為 3動詞、3名詞、3形容詞、1副詞。

2. **15 級分 RPG 遊戲化系統 (Gamification)**
   - **學測 15 級分天梯**：從 `Lv.1 詞彙新兵` 一路升級至 `Lv.15 學測滿級分戰神`。
   - **經驗值 (EXP) 與連勝機制**：一般答對獲得 +15 EXP，連對觸發連勝加成（Combo Multiplier）。
   - **成就徽章系統**：解鎖「初入試煉」、「十連斬神射」、「錯題粉碎者」、「長期記憶固化」等 8 大榮譽徽章。

3. **艾賓浩斯黃金間隔重複演算法 (Leitner 5-Box Spaced Repetition)**
   - 根據認知心理學遺忘曲線，動態排程題目複習週期：
     - **Box 1 (弱點錯題盒)**：每日 / 明日必測（答錯立即降回此盒重新歷練）。
     - **Box 2 (初見成效盒)**：間隔 3 天重測。
     - **Box 3 (掌握熟練盒)**：間隔 7 天重測。
     - **Box 4 (長期記憶盒)**：間隔 14 天重測。
     - **Box 5 (永久滿級分盒)**：間隔 30 天，徹底固化進長期記憶庫。
   - **除錯懸賞激勵 (Bounty EXP)**：消滅 Box 1 錯題獲得額外 **+25 EXP 雙倍賞金**，化挫折為動力。
   - **今日待複習警報**：每天打開系統，自動過濾出到達遺忘臨界點的到期題目。

4. **詞彙 × 英文作文無縫接軌 (Writing Scaffolds)**
   - 每題解析皆配備**「✍️ 作文直接帶走・高分句型鷹架」**。
   - 涵蓋青年志向、生活科技利弊、社會議題反思、心態情緒描寫等常考學測作文情境。

5. **本地持久化存檔與多設備同步 (Persistence)**
   - 所有作答紀錄、等級、EXP 與艾賓浩斯排程自動儲存於瀏覽器 `localStorage`，重開機永不遺失。
   - 提供「💾 匯出進度檔 (JSON)」與「📥 匯入進度檔」，支援筆電、平板與手機無縫切換。

---

## 📂 專案目錄結構 (Project Architecture)

本專案完全基於標準靜態 Web 架構設計，**無任何外部依賴套件**，可直接於本機雙擊開啟，或一鍵發布至 **GitHub Pages**：

```text
├── index.html                   # 滿級分備考平台總入口 (GitHub Pages 首頁)
├── vocab-quiz.html              # 核心：詞彙題 15 級分 RPG 測驗 & 艾賓浩斯間隔複習系統
├── collocations.html            # 1,500 組學測滿級分核心搭配詞大典
├── writing-guide.html           # 學測英文作文滿級分自學講義
├── grammar-guide.html           # 歷屆文法考點完整大全與全卷題型破題攻略
│
├── data/                        # 核心 JSON 資料庫目錄
│   ├── vocab_questions_database.json   # 106~115 全 125 題詞彙真題 (含 100% 詞性、解析、寫作鷹架)
│   ├── master_collocations_1500.json   # 1,500 組主題分類搭配詞庫
│   ├── vocab_reference.json            # 大考中心 6,350 字級官方字典庫
│   ├── exam_vocab_analysis.json        # 歷屆大數據分析結果
│   └── exams_corpus.json               # 歷屆學測考卷語料庫
│
├── docs/                        # 參考文獻與官方檔案
│   ├── 高中英文參考詞彙表(111學年度起適用).pdf
│   ├── 簡報.pdf
│   ├── 演講逐字稿.txt
│   └── 各種資料網址.txt
│
├── .agents/                     # AI Agent 自訂技能 (Skills)
│   └── skills/
│       └── ceec-vocab-item-writer/
│
├── README.md                    # 本專案說明文件
└── .gitignore                   # Git 版本控制忽略設定
```

---

## 📅 高二上學期 90 天極速掌握學習時間軸 (Syllabus)

高二上學期距離學測擁有將近 14 個月的時間優勢。每日僅需投注 **15~20 分鐘**，無痛融入日常作息：

| 階段 | 時間週期 | 每日核心任務 (15~20 min) | 遊戲等級目標 |
| :--- | :--- | :--- | :--- |
| **第一階段：真題破壁・建立題感** | Day 1 ~ 21 (3週) | 完成 1 回 (10題) 歷屆真題 + 消化 3 題錯題 | 晉升至 **Lv. 7 搭配詞獵人** |
| **第二階段：主題攻堅・無死角網羅** | Day 22 ~ 63 (6週) | 研讀 1,500 組主題搭配詞 + 艾賓浩斯排程重測 + 寫作鷹架記誦 | 晉升至 **Lv. 11 前標守護者** |
| **第三階段：五級魔王題與陷阱排雷** | Day 64 ~ 84 (3週) | 專攻 Level 5 鑑別度字彙與 50 組形音易混淆字（adapt/adopt 等） | 晉升至 **Lv. 14 頂標先鋒將軍** |
| **第四階段：極速秒殺與滿級分固化** | Day 85 ~ 90 (1週) | 隨機 10 題限時 3.5 分鐘全真盲測 + 將所有錯題清空晉級至 Box 5 | 登頂 **Lv. 15 學測滿級分戰神** 👑 |

---

## 🚀 如何發布至 GitHub Pages (免費線上使用)

1. **建立 GitHub Repository**：
   在 GitHub 上建立一個新的公開或私有儲存庫（例如 `ceec-english-mastery`）。
2. **推送專案檔案**：
   ```bash
   git init
   git add .
   git commit -m "feat: initial commit of CEEC English Mastery Platform"
   git branch -M main
   git remote add origin https://github.com/<YOUR_USERNAME>/ceec-english-mastery.git
   git push -u origin main
   ```
3. **開啟 GitHub Pages**：
   - 進入儲存庫的 **Settings** -> **Pages**。
   - 在 **Build and deployment** 下的 **Branch** 選擇 `main` 分支與 `/(root)` 目錄。
   - 點擊 **Save**。
   - 幾秒鐘後即可透過 `https://<YOUR_USERNAME>.github.io/ceec-english-mastery/` 在任何手機、平板或電腦上免安裝直接使用！

---

## 🔮 未來擴充路線圖 (Roadmap)

- [ ] **閱讀測驗長難句結構拆解器**：針對學測閱測高頻分詞構句與名詞子句進行語義色彩視覺化標註。
- [ ] **英文作文 AI 智能批改介面**：銜接大考中心評分規準之文法糾錯與頂標詞彙替換建議。
- [ ] **高中英聽全真情境模擬庫**：整合短篇對話與長篇聽解常見陷阱題型。

---
*Created for Excellence in CEEC English Exam Preparation.*
