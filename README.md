# 🏃 世界必跑絕景馬拉松導覽（World Scenic Marathons LLM Wiki）

> **一站式全球 12 場殿堂級馬拉松跑旅百科 ｜ 4 大跨賽事主題索引 ｜ 13 份極簡紙質互動簡報**  
> 彙整賽事規格、賽道路況、魔王路段、報名抽籤/體檢、交通後勤與氣候裝備的雙向鏈結知識圖譜。

---

## 📖 專案簡介

《世界必跑絕景馬拉松導覽》是一套結合長跑耐力運動與全球跑旅（Racecation）的專業知識圖譜。專案以消除跑者出國參賽的「資訊落差」為核心目標，系統化收錄橫跨全球五大洲的 12 場代表性全程馬拉松（42.195 km）。

本專案採**模組化分離架構**，將 Markdown 知識庫與 HTML 互動簡報分類存放於獨立資料夾中：
1. **[World_Scenic_Marathons/](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/tree/main/World_Scenic_Marathons)（Markdown Wiki 筆記庫）**：採用 Obsidian 雙向鏈結（`[[賽事名稱]]`）與 YAML Frontmatter 構建，分為「總首頁 (MOC) ➔ 四大主題樞紐 (Hubs) ➔ 十二場賽事手冊 (Leaves)」三層網絡。（點擊可直接在 GitHub 倉庫檢視）
2. **[World_Scenic_Marathons_HTML/](World_Scenic_Marathons_HTML/00_世界必跑絕景馬拉松_首頁索引.html)（HTML 互動簡報系統）**：採用純前端 HTML/CSS/JS 實作，內建 1 份 8 頁總索引導航中心與 12 份各 7 頁獨立賽事簡報（共 92 頁），支援全螢幕演示與星狀雙向跳轉。（點擊可線上開啓簡報展示）

---

## 🧭 Wiki 核心筆記與賽事索引（World_Scenic_Marathons）

> 💡 **點擊下方連結可直接在 GitHub 上線上閱讀排版完整的 Wiki 筆記：**

### 🏠 總首頁與知識地圖
* 🗺️ **[00_世界必跑絕景馬拉松_首頁索引.md](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/00_世界必跑絕景馬拉松_首頁索引.md)**  
  整座知識庫的指揮中心，包含架構圖、四大主題分類、12 場賽事全覽矩陣與多維度跑者決策導航。

---

### 📚 四大跨賽事主題樞紐（Topic Hubs）
* 🏛️ **[世界馬拉松大滿貫與經典城市賽道.md](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/世界馬拉松大滿貫與經典城市賽道.md)**：都會競速、平坦賽道、世界紀錄、慈善募款與抽籤/BQ攻略。
* ⛰️ **[極限地形與山岳沙漠挑戰.md](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/極限地形與山岳沙漠挑戰.md)**：高山垂直爬升、荒漠軟沙戈壁、海岸懸崖強逆風與野外險坡。
* 🌿 **[世界遺產與自然荒野賽道.md](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/世界遺產與自然荒野賽道.md)**：聯合國 UNESCO 世界遺產、千年古蹟神廟、無圍欄野生動物棲息地。
* 📅 **[全球四季跑旅日曆.md](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/全球四季跑旅日曆.md)**：1 至 12 月全球四季賽期、訓練節奏與跨國跑旅倒數時程手冊。

---

### 🏆 十二場世界必跑絕景馬拉松深度指南（Race Guides）

| 賽事名稱 | 舉辦月份 | 地區 / 城市 | 地貌特徵與難度 | 賽事亮點與核心價值 | GitHub Wiki 筆記 | 線上互動簡報 |
| :--- | :---: | :--- | :---: | :--- | :--- | :--- |
| **日本東京馬拉松** | **3月** | 🇯🇵 日本・東京 | 都會極平公路（初級） | 亞洲六大滿貫首選、日式私補盛宴、96% 超高完賽率 | [📖 閱讀筆記](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/日本東京馬拉松.md) | [🖥️ 查看簡報](World_Scenic_Marathons_HTML/日本東京馬拉松.html) |
| **義大利羅馬馬拉松** | **3月** | 🇮🇹 義大利・羅馬 | 古城平路＋石板路（中等） | 競技場出發衝線、穿梭梵蒂岡與老城、海外跑者免體檢 | [📖 閱讀筆記](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/羅馬馬拉松.md) | [🖥️ 查看簡報](World_Scenic_Marathons_HTML/羅馬馬拉松.html) |
| **英國倫敦馬拉松** | **4月** | 🇬🇧 英國・倫敦 | 泰晤士河平緩（初級） | 格林威治起跑、登上倫敦塔橋、全球最大單日慈善嘉年華 | [📖 閱讀筆記](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/倫敦馬拉松.md) | [🖥️ 查看簡報](World_Scenic_Marathons_HTML/倫敦馬拉松.html) |
| **美國大瑟爾國際馬拉松** | **4月** | 🇺🇸 美國・加州 | 太平洋海岸丘陵（高） | 加州一號公路絕景、波濤太平洋懸崖、颶風角 2 英里爬坡 | [📖 閱讀筆記](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/美國大瑟爾國際馬拉松.md) | [🖥️ 查看簡報](World_Scenic_Marathons_HTML/美國大瑟爾國際馬拉松.html) |
| **南非五大野生動物馬拉松** | **6月** | 🇿🇦 南非・恩塔貝尼 | 原始草原荒野（極高） | 無人工圍欄直面非洲五霸巨獸、武裝巡邏員、43 度黃木谷陡坡 | [📖 閱讀筆記](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/南非五大野生動物馬拉松.md) | [🖥️ 查看簡報](World_Scenic_Marathons_HTML/南非五大野生動物馬拉松.html) |
| **柬埔寨吳哥窟王朝馬拉松** | **8月** | 🇰🇭 柬埔寨・暹粒 | 古蹟林蔭公路（中高） | 黎明微曦穿越小吳哥與巴戎寺微笑佛陀、人道關懷與靈性奔馳 | [📖 閱讀筆記](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/吳哥窟王朝馬拉松.md) | [🖥️ 查看簡報](World_Scenic_Marathons_HTML/吳哥窟王朝馬拉松.html) |
| **瑞士少女峰馬拉松** | **9月** | 🇨🇭 瑞士・因特拉肯 | 高山攀升 1,953m（極高） | 艾格峰與少女峰萬年冰河伴跑、惡名昭彰溫根壁、海拔 2,320m 終點 | [📖 閱讀筆記](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/少女峰馬拉松.md) | [🖥️ 查看簡報](World_Scenic_Marathons_HTML/少女峰馬拉松.html) |
| **約旦佩特沙漠馬拉松** | **9月** | 🇯🇴 約旦・佩特拉 | 玫瑰古城＋軟沙（極高） | 清晨包場世界遺產玫瑰古城、穿越中東極端乾燥高溫紅砂沙漠 | [📖 閱讀筆記](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/約旦佩特沙漠馬拉松.md) | [🖥️ 查看簡報](World_Scenic_Marathons_HTML/約旦佩特沙漠馬拉松.html) |
| **德國柏林馬拉松** | **9月** | 🇩🇪 德國・柏林 | 世界最快柏油路（初級） | 13 次世界紀錄誕生地、全球破 PB 首選、秋高氣爽布蘭登堡門衝線 | [📖 閱讀筆記](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/德國柏林馬拉松.md) | [🖥️ 查看簡報](World_Scenic_Marathons_HTML/德國柏林馬拉松.html) |
| **希臘雅典經典馬拉松** | **11月** | 🇬🇷 希臘・雅典 | 21km 連續爬升（高） | 追尋 2,500 年史詩足跡、全大理石帕那辛奈克體育場衝線 | [📖 閱讀筆記](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/雅典經典馬拉松.md) | [🖥️ 查看簡報](World_Scenic_Marathons_HTML/雅典經典馬拉松.html) |
| **紐西蘭皇后鎮馬拉松** | **11月** | 🇳🇿 紐西蘭・皇后鎮 | 硬質碎石湖畔（中等） | 號稱地球上最美的馬拉松、箭鎮淘金小徑、海耶斯湖與卓越山脈倒影 | [📖 閱讀筆記](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/紐西蘭皇后鎮馬拉松.md) | [🖥️ 查看簡報](World_Scenic_Marathons_HTML/紐西蘭皇后鎮馬拉松.html) |
| **日本富士山馬拉松** | **11月** | 🇯🇵 日本・河口湖 | 雙湖環湖微坡（中等） | 深秋火紅楓葉迴廊、清晨逆富士倒影、21km 激坂坡挑戰 | [📖 閱讀筆記](https://github.com/yangrainie/World_Scenic_Marathons_LLM_Wiki/blob/main/World_Scenic_Marathons/日本富士山.md) | [🖥️ 查看簡報](World_Scenic_Marathons_HTML/日本富士山.html) |

---

## 🖥️ 互動簡報系統（World_Scenic_Marathons_HTML）

所有 HTML 投影片均獨立集中存放於 `World_Scenic_Marathons_HTML/` 資料夾，具備純前端、零依賴、Notion/Muji 紙本美學風格：
- **首頁總索引簡報**：[00_世界必跑絕景馬拉松_首頁索引.html](World_Scenic_Marathons_HTML/00_世界必跑絕景馬拉松_首頁索引.html)（8 頁導航中心）
- **新手教學簡報**：[世界必跑絕景馬拉松_新手教學簡報.html](World_Scenic_Marathons_HTML/世界必跑絕景馬拉松_新手教學簡報.html)
- **12 場獨立深度簡報**：每場 7 頁，涵蓋「賽事名片 ➔ 規格數據 ➔ 魔王路段與未裁切完整路線圖 ➔ 報名資格與體檢 ➔ 住宿後勤 ➔ 裝備補給 ➔ 賽後觀光與下一站跳轉」。
- **操作快捷鍵**：
  - `←` / `→`：前後切換投影片
  - `F`：切換全螢幕簡報模式
  - `Home`：一鍵返回第 1 頁
  - 頁面按鈕：即時跳轉至首頁索引或相鄰賽事

---

## 📁 檔案結構

```text
World_Scenic_Marathons_LLM_Wiki/
├── .gitignore                          # 忽略 .obsidian 等暫存與快取
├── README.md                           # GitHub 專案首頁說明與導覽
├── images/                             # 根目錄賽事照片與完整路線圖 (53 張)
│
├── World_Scenic_Marathons/             # 📖 專屬 Markdown Wiki 筆記資料夾
│   ├── index.html                      # 筆記庫網頁導航中心 (防止 Pages 404)
│   ├── 00_世界必跑絕景馬拉松_首頁索引.md   # Wiki 總首頁
│   └── *.md                            # 12 場賽事深度 Wiki 筆記與四大主題分類
│
└── World_Scenic_Marathons_HTML/        # 🖥️ 專屬 HTML 互動簡報資料夾
    ├── index.html                      # 預設簡報首頁 (防止 Pages 404)
    ├── 00_世界必跑絕景馬拉松_首頁索引.html # 首頁總索引互動簡報 (8 頁)
    ├── 世界必跑絕景馬拉松_新手教學簡報.html # 新手教學導航簡報
    ├── *.html                          # 12 場賽事極簡紙質簡報 (各 7 頁)
    └── images/                         # 簡報所需之完整圖片資源
```

---

## 🛠️ 開發與維護環境

- **編輯器**：Obsidian / Visual Studio Code
- **排版規範**：GitHub Flavored Markdown (GFM)
- **視覺風格**：Notion / Muji Earth Tone（低飽和米白紙質底色、墨色文字與安全置中排版）
