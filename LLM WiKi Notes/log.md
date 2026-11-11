# 系統日誌 (System Log)

本檔案為 append-only 流水帳記錄，記錄所有知識庫的 Ingest、Query 與 Lint 操作。

---

## [2026-11-11] init | System Architecture Setup
- 建立系統行動憲章 `AGENTS.md`，定義角色人設、三層架構與三大核心工作流（Ingest, Query, Lint）。
- 建立目錄架構：`raw/books/`, `wiki/concepts/`, `wiki/methods/`, `wiki/playbooks/`, `wiki/comparisons/`。
- 初始化 `index.md` 與 `log.md`。

## [2026-11-11] ingest | 5 篇核心時間管理與抗拖延經典文獻
- 匯入並深度萃取以下 5 篇經典著作至 `raw/books/`：
  - `01_atomic_habits_core.md` (原子習慣)
  - `02_procrastination_psychology_core.md` (拖延心理學)
  - `03_deep_work_core.md` (深度工作力)
  - `04_gtd_workflow_core.md` (搞定 GTD)
  - `05_procrastination_equation_core.md` (拖延方程式)

## [2026-11-11] compile | Wiki 知識層與大學生實戰劇本初版編譯
- 編譯 6 篇核心機制至 `wiki/concepts/`：
  - `雙曲貼現 (Hyperbolic Discounting)`
  - `完美主義癱瘓 (Perfectionism Paralysis)`
  - `注意力殘留 (Attention Residue)`
  - `深度工作 vs 淺薄工作 (Deep Work vs Shallow Work)`
  - `習慣迴路 (Habit Loop)`
  - `拖延方程式 (The Procrastination Equation)`
- 編譯 5 篇實戰工具至 `wiki/methods/`：
  - `兩分鐘定律 (Two-Minute Rule)`
  - `時間塊排程 (Time Blocking)`
  - `下一步行動法 (Next Action Method)`
  - `環境摩擦力工程 (Friction Engineering)`
  - `非排程表 (The Unschedule)`
- 落地 3 篇大學生高優先級劇本至 `wiki/playbooks/`：
  - `大學生期末考多科集中爆炸排程 (Finals Week Crisis Management)`
  - `突破白紙恐懼：大專論文與報告零阻力起步 (Breaking Blank Page Syndrome)`
  - `擊碎白天耍廢晚上罪惡感的惡性循環 (Breaking Guilt & Revenge Bedtime Procrastination)`
- 建立 2 篇工具取捨比較至 `wiki/comparisons/`：
  - `番茄工作法 vs 時間塊：何時該切換模式 (Pomodoro vs Time Blocking)`
  - `GTD vs 簡約待辦清單：大學生的低維護取捨 (GTD vs Minimalist List)`
- 完成全域索引 `index.md` 雙向鏈結建置。

## [2026-11-11] config | 學術文獻與 PDF 流程升級 (rawpapers)
- 於 `AGENTS.md` 新增「第 4 節：資料來源獲取與處置規範 (Source Acquisition Protocol)」。
- 建立專屬論文資料夾 `raw/papers/`，並在專案根目錄建立目錄交會點軟連結 `rawpapers/` 直通該資料夾。
- 明訂對話傳入 PDF 與 arXiv 連結自動轉換下載至 `raw/papers/`（`rawpapers/`）之標準作業流程。
- 建立 `raw/articles/` 與 `raw/user_cases/` 擴充資料夾。

## [2026-11-11] ingest | 對話上傳 PDF《大學生高效時間管理與抗拖延 核心文獻與心法摘要》
- 依據 `AGENTS.md` 規範，將原始 PDF 文本完整保存至 `raw/papers/2026-11-11_大學生高效時間管理與抗拖延_核心文獻與心法摘要.md`（同步反映於 `rawpapers/`）。
- 執行多頁編譯 (Multi-Page Touch)：
  - 新增實踐工具頁：`wiki/methods/習慣堆疊 (Habit Stacking).md`（神經突觸錨定、餐後/就寢抗拖延微配方）。
  - 新增實踐工具頁：`wiki/methods/番茄工作法 (Pomodoro Technique).md`（25/5 循環、強制斷網休息、每日 4-5 小時認知紅線與超標 Loop 篩減機制）。
  - 增補概念頁：`wiki/concepts/雙曲貼現 (Hyperbolic Discounting).md`（增補即時獎賞替代策略）。
  - 增補工具頁：`wiki/methods/時間塊排程 (Time Blocking).md`（增補深度工作啟動儀式 Startup Ritual）。
  - 增補劇本頁：`wiki/playbooks/大學生期末考多科集中爆炸排程 (Finals Week Crisis Management).md`（整合 4-5 小時防彈上限與 Loop 淘汰防線）。
- 更新 `index.md` 與 `log.md`。

## [2026-11-11] ingest | 對話上傳第二份資料《高效時間管理與抗拖延實戰手冊》
- 原始 PDF 文本歸檔至 `raw/papers/2026-11-11_高效時間管理與抗拖延實戰手冊_大專院校學生與小資族專用.md`（同步反映於 `rawpapers/`）。
- 執行多頁編譯 (Multi-Page Touch)：
  - 新增概念頁：`wiki/concepts/AI 自動排程演算法 (AI Scheduling Graph & Loop).md`（Graph/Loop 架構、工時上限硬約束、剪枝與拆細重排）。
  - 新增實踐工具頁：`wiki/methods/1-3-5 待辦法則 (1-3-5 Rule).md`（1大3中5小限額、工時預算克服規劃謬誤）。
  - 新增實踐工具頁：`wiki/methods/艾森豪矩陣 (Eisenhower Matrix).md`（四象限決策、學生與小資族場景對齊）。
  - 新增實踐工具頁：`wiki/methods/時間管理自我檢查表 (Anti-Procrastination Checklist).md`（開工前 2 分鐘環境、拆解與工具查核）。
  - 新增比較頁面：`wiki/comparisons/數位筆記工具大比拼：Notion vs Obsidian vs Logseq.md`（四大維度評比、防假性勤奮折騰）。
- 更新 `index.md` 與 `log.md`。

## [2026-11-11] query/presentation | 生成 Marp 專題投影片《LLM在教學上的運用問題與認知突圍》
- 建立專屬產出目錄 `wiki/presentations/`。
- 調用庫內認知機制（深度工作力、假性勤奮、注意力殘留、拖延方程式、完美主義與評量失靈），編譯完成標準 Marp 投影片檔案：`wiki/presentations/LLM在教學上的運用問題與認知突圍.md`。
- 更新 `index.md` 與 `log.md`。

## [2026-11-11] query/presentation | 生成互動式 HTML 投影片《LLM在教學上的運用問題與認知突圍.html》
- 依據使用者需求，將專題投影片編譯為**獨立式、零外部相依的互動 HTML 簡報**：`wiki/presentations/LLM在教學上的運用問題與認知突圍.html`。
- 內建進度條、全螢幕切換、鍵盤快捷鍵（方向鍵/空白鍵翻頁）與自適應 16:9 卡片排版。
- 同步更新 `index.md` 與 `log.md`。

## [2026-11-11] design/refactor | 升級 HTML 投影片為 Kinfolk 文青風格
- 依據使用者選擇，全面重構 `wiki/presentations/LLM在教學上的運用問題與認知突圍.html`：
  - **色調氣質**：Kinfolk 極簡冷淡風（象牙白手工紙質底色 `#FBF9F5`、深炭墨黑文字 `#1F2326`、高對比與單一低飽和陶土紅 `#B4533C` 點綴）。
  - **字體混搭**：標題與金句採用典雅「思源宋體 (Noto Serif TC)」，內文卡片採用清爽「思源黑體 (Noto Sans TC)」。
  - **版面節奏**：和風微卡片流（6px 柔和微圓角、細緻邊框、莫蘭迪印記標籤、雙引號金句盒與 `01 / 12` 兩位數極簡導航）。
- 更新 `log.md`。

## [2026-11-11] query/handout | 生成圖文講義型 HTML《LLM在教學上的運用問題與認知突圍_圖文講義.html》
- 建立專屬講義資料夾 `wiki/handouts/`。
- 採用日系無印 / 莫蘭迪大地色系（手工和紙白 `#FAF8F5`、鼠尾草綠 `#4E6E58`、陶土紅 `#B85D43`）與思源宋體/黑體混搭排版。
- 內嵌三大手繪風格向量圖解 (SVG)：
  - 【圖解 1.1】深度認知掙扎 vs 外部直接卸載之神經突觸路徑
  - 【圖解 2.1】AI 介入前後之動機變數失衡天平
  - 【圖解 4.1】LLM Wiki 三層複利知識編譯架構
- 包含 Prompt 實戰對比表、過程性評量教案指引、互動式課後自我檢核清單，並內建列印專用排版（支援一鍵 Print to PDF）。
- 更新 `index.md` 與 `log.md`。
