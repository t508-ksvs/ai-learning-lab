# 張老師的 AI 教材實驗室

以 GitHub Pages 保存與發布的 AI 教材入口，由「張老師的園丁天地」及後續教師教材專案整理而來。

## 網站與原始碼

- 網站：https://t508-ksvs.github.io/ai-learning-lab/
- GitHub：https://github.com/t508-ksvs/ai-learning-lab
- 原站：https://sites.google.com/a/ksvs.kh.edu.tw/misszhang0119
- 收錄19筆教材：字根詞彙、文法句作、考試準備、化工與汽車PVQC。
- 含31–50核心字兩版，以及新發布的PVQC化學字根「講義版」「學生學習版」。

功能：主題篩選、搜尋、瀏覽器本機收藏、教材詳情與來源、三種學習路徑。收藏不跨裝置同步；練習在原教材開啟。

## 檔案分工

- index.html：首頁、導覽與內容區塊。
- style.css：版面與響應式樣式。
- app.js：教材資料及搜尋、分類與收藏。
- .nojekyll：直接發布靜態檔案。

不需要建置或安裝套件。Google Fonts 無法連線時會使用系統字型。

## 更新教材

1. 在 app.js 的 resources 陣列加入或調整教材，保留穩定 id。
2. 填寫 title、category、format、desc、url、source、visual、sub、mark、tone；需要版本說明時補 note。
3. 用 node --check app.js 檢查語法，核對教材連結、來源、版本與功能說明。
4. 瀏覽器檢查搜尋與分類；提交並推送到 main。
5. 等待 GitHub Pages 部署完成，再確認正式網址。

GitHub 網頁編輯器也能編輯原始檔；main 分支根目錄為 Pages 發布來源。跨電腦請先拉取最新版本，不同 Agent 避免同時修改同一檔案。

## 2026-11-02 遷移紀錄

依使用者要求，由 ChatGPT Sites 最新18筆版本建立獨立 GitHub 專案。公開 repository 僅包含靜態網站與說明，不包含 Sites 憑證、託管設定或私人交接資料。

PVQC化學教材來源：https://t508-ksvs.github.io/pvqc-chemistry-root-learning/

包含四個圖文代表主題、541個原字表詞彙及另列的六個概念延伸詞；不宣稱全部課程完成。講義版與學生版共用素材，各自保留入口。

## 驗證範圍

原版已做搜尋、篩選、收藏、詳情與窄螢幕檢查；遷移版檢查18筆清單、新PVQC入口、原始碼語法與發布檔案。外部教材的登入、語音及完整操作仍依原站與裝置情況。

## 2026-11-02 統測複習講義入口

依使用者指定，新增 https://t508-ksvs.github.io/aimix-screen-handout-html/exam-review/ 到「考試準備」，名稱為「統測英文複習講義・HTML 電子版」，總計19筆教材。保留原教材內容與網址。
