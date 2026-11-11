---
marp: true
theme: default
paginate: true
header: "LLM Wiki 實戰專題 · 高等教育與認知科學"
footer: "高效時間管理與抗拖延研究組 | 繁體中文版"
style: |
  section {
    font-family: 'PingFang TC', 'Microsoft JhengHei', sans-serif;
    font-size: 24px;
    padding: 40px;
    background-color: #fcfdfd;
  }
  h1 {
    color: #1e3a8a;
    font-size: 40px;
  }
  h2 {
    color: #1d4ed8;
    font-size: 32px;
    border-bottom: 2px solid #e2e8f0;
    padding-bottom: 8px;
  }
  h3 {
    color: #0f766e;
    font-size: 26px;
  }
  strong {
    color: #b91c1c;
  }
  blockquote {
    background: #f1f5f9;
    border-left: 6px solid #3b82f6;
    padding: 10px 18px;
    border-radius: 4px;
    font-size: 20px;
  }
  .highlight {
    background-color: #fef08a;
    padding: 2px 6px;
    border-radius: 4px;
  }
  .badge {
    display: inline-block;
    padding: 4px 10px;
    border-radius: 12px;
    font-size: 16px;
    font-weight: bold;
    color: white;
  }
  .badge-red { background-color: #ef4444; }
  .badge-blue { background-color: #3b82f6; }
  .badge-green { background-color: #10b981; }
---

# LLM 在高等教學上的運用問題與認知突圍
### 從神經科學、深度工作力到抗拖延的系統化剖析

**報告人**：LLM Wiki 認知行為與個人效能架構師  
**適用對象**：大專院校師生、教育工作者、小資自我學習者  
**理論基底**：認知負荷理論 · 深度工作力 · 拖延方程式 · 行為習慣架構

---

## 📑 簡報全景導覽 (Agenda)

1. **現況與矛盾**：生成式 AI 狂潮下的課堂衝擊
2. **五大深層運用困境**（以 Wiki 底層機制解析）：
   * 困境一：過度認知卸載與「假性勤奮」陷阱
   * 困境二：即時多巴胺對內在動機的瓦解
   * 困境三：批判性思維萎縮與「白紙恐懼」變形
   * 困境四：學術誠信危機與傳統評量失靈
   * 困境五：幻覺偏誤與自動化信任盲區
3. **教育範式重構**：教師端與學生端的雙向突圍指南
4. **實戰工具整合**：如何用 LLM Wiki 實現高價值主動學習

---

## ⚠️ 核心衝突：效率神話 vs 深度學習

> 「當產出變得極度廉價，『思考過程』本身的價值何在？」

* **表象繁榮**：
  * 大學生用 10 秒生成 2000 字課堂報告。
  * 程式作業一鍵 Prompt 完成，投影片一鍵自動排版。
* **暗藏危機**：
  * **學習曲線被扁平化**：跳過了「卡關—思索—神經元重塑」的痛苦必要區間。
  * **教學現場信任赤字**：教師疲於使用 AI 偵測器抓弊，學生深陷「用 AI 寫作業給 AI 批改」的虛無荒謬循環。

---

## 困境一：過度認知卸載與「假性勤奮」
<span class="badge badge-red">認知神經機制</span> 關聯頁面：`[[深度工作 vs 淺薄工作 (Deep Work vs Shallow Work)]]`

* **認知卸載 (Cognitive Offloading)**：
  * 人類大腦遵循「最省力原則」。當 LLM 能瞬間給出結論，大腦前額葉會本能停止高階運算。
* **假性勤奮 (Pseudo-Work) 的升級**：
  * 過去的假性勤奮是「換螢光筆劃線、抄筆記」。
  * **現在的假性勤奮是「下了 30 個精美 Prompt、生成了 50 頁 PDF，但腦袋裡空空如也」**。
* **核心代價**：學生產出了完美的報告，卻失去了對知識的**工作記憶固化能力**。

---

## 困境二：即時多巴胺對學習動機的瓦解
<span class="badge badge-red">動機理論</span> 關聯頁面：`[[拖延方程式 (The Procrastination Equation)]]`、`[[雙曲貼現 (Hyperbolic Discounting)]]`

$$\text{動機強度 (Motivation)} = \frac{\text{期望 (Expectancy)} \times \text{價值 (Value)}}{\text{衝動性 (Impulsiveness)} \times \text{延遲 (Delay)}}$$

* **延遲 ($Delay$) 與衝動性 ($Impulsiveness$) 被極度惡化**：
  * 過去：需要耗時 3 天查文獻，學生會安排時間塊逐步推進。
  * 現在：知道「死線前 15 分鐘讓 LLM 吐出全文即可」，主觀回饋延遲被無限延後，**導致學期中的拖延與耍廢更趨嚴重**。
* **期望 ($Expectancy$) 的虛假膨脹**：
  * 誤把「工具的能力」當成「自己的能力」，引發嚴重的能力錯覺。

---

## 困境三：思考肌肉萎縮與「白紙恐懼」變形
<span class="badge badge-red">心理抗拒</span> 關聯頁面：`[[完美主義癱瘓 (Perfectionism Paralysis)]]`

* **白紙恐懼 (Blank Page Syndrome) 的變種**：
  * 原本的白紙恐懼：面對空白 Word 不知如何下筆。
  * **現在的依賴症候群**：如果不先向 ChatGPT / Claude 問一個開頭，學生甚至喪失了「構思第一個論點」的原生勇氣。
* **內在批判官的隱形退化**：
  * 寫作的本質是思考的提煉（海明威的爛初稿原則）。
  * 直接要求 LLM 給出結構工整的文章，剥奪了學生在混亂想法中**自我辯證與概念抽象化**的核心鍛鍊。

---

## 困境四：學術誠信危機與傳統評量失靈
<span class="badge badge-red">體系衝突</span> 關聯頁面：`[[GTD vs 簡約待辦清單：大學生的低維護取捨]]`

* **「成果交付導向 (Outcome-Only Assessment)」的崩潰**：
  * 期末書面報告、申論題作業、課後 Take-home Exam 已經失去檢驗真實知識理解的功能。
* **AI 偵測器 (AI Detector) 的死胡同**：
  * 學術界實驗證實：AI 檢測軟體具備極高的偽陽性 (False Positive) 與偽陰性。
  * 造成師生關係對立，學生遭受無端質疑，教師精力被防弊行政瑣事嚴重耗損。

---

## 困境五：幻覺偏誤與「自動化信任盲區」
<span class="badge badge-red">批判性失焦</span> 關聯頁面：`[[注意力殘留 (Attention Residue)]]`

* **權威感幻覺 (Hallucination)**：
  * LLM 擅長用极其自信、流暢且具說服力的語調生成虛假文獻、錯誤公式或歷史事實。
* **缺乏批判性查核 (Automation Bias)**：
  * 大學生常因時間緊迫（死線前夕），直接複製貼上 LLM 生成的註腳與參考文獻，失去文獻溯源 (Ground Truth Verifiability) 的學術基本功。
* **資訊同質化 (Homogenization of Thought)**：
  * 全班繳交的報告結構、論點切入角如出一轍，缺乏批判性、異端思考與個人生活經驗的融入。

---

## 💡 教師端的教學典範重構 (Pedagogical Redesign)
<span class="badge badge-green">行動解方</span>

1. **從「評量結果」轉向「評量過程 (Process-based Assessment)」**：
   * 引入課堂口頭辯論、即席白板推導、無插電思考筆記。
   * 要求學生繳交「Prompt 迭代日誌 + 自己對 AI 輸出的批改註記」。
2. **設計「逆向防 AI」題型**：
   * **在地化與個人經驗**：結合校園在地田野調查、個人實習案例。
   * **AI 糾錯挑戰題**：提供一份充滿 LLM 常見幻覺的論文草稿，要求學生查核出 5 個邏輯與事實錯誤。
3. **角色轉變**：教師從「知識轉錄者」變為「高階認知教練」。

---

## 🚀 學生端的學習突圍指南 (Student Playbook)
<span class="badge badge-blue">實踐處方</span> 關聯工具：`[[下一步行動法 (Next Action Method)]]`、`[[時間塊排程 (Time Blocking)]]`

* **鐵律：將 LLM 視為「思維陪練員」，而非「代寫槍手」**
  * ❌ 錯誤用法：「請幫我寫一篇 2000 字探討社群媒體對心理健康影響的報告。」
  * ✅ 正確用法：「我初步提出以下 3 個論點，請你扮演批判我的反方學者，指出我論證最薄弱的 2 個邏輯漏洞。」
* **「先思考 15 分鐘」原則**：
  * 運用 `[[兩分鐘定律 (Two-Minute Rule)]]`，先親手在紙上寫下自己的骨架，再向 AI 提問，杜絕一開始就放棄大腦主導權。
* **保護深度心流**：
  * 寫作時將 AI 視窗關閉，使用 `[[番茄工作法 (Pomodoro Technique)]]`，只在後續查核時統一開啟批次處理。

---

## 🧠 用「LLM Wiki」範式引領高等自學
<span class="badge badge-green">終極模式</span> 知識複利與持續編譯架構

```
傳統消極模式：
問問題 ──> LLM 吐出答案 ──> 複製貼上 ──> 關閉視窗 (大腦無累積)

LLM Wiki 主動建構模式：
原始來源 (PDF/文獻) ──> 深度閱讀與標記 ──> LLM 協助提煉結構 
        ↓
寫入個人本地 Vault (Obsidian) ──> 建立雙向鏈結 [[Page Name]] 
        ↓
持續累積、發現矛盾、形成個人觀點 (知識真正沉澱為能力)
```

* **人的職責**：策展來源、提出好問題、保持批判懷疑、決定價值取向。
* **LLM 的職責**：處理雜務、整理交叉引用、維護索引、加速編譯。

---

## 🎯 結語：在生成式時代，真正的核心競爭力

> 「AI 不會取代深度思考的人，但只會使用 AI 進行淺薄產出的人，將最先被取代。」

* **前額葉皮質的「痛苦思索」不是 bug，而是學習的 feature**。
* **抗拖延的終極之道**：
  不是尋求更快速的自動化工具來逃避焦慮，而是**主動掌控注意力、劃定深度工作區間，並與 AI 建立健康互補的協同關係**。

---

# 謝謝聆聽 · 歡迎交流討論
### Q & A / 交流討論

* 投影片來源歸檔：`wiki/presentations/LLM在教學上的運用問題與認知突圍.md`
* 關聯實戰手冊：`LLM Wiki Notes/index.md`
