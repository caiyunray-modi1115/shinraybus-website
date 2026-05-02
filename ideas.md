# 台灣新睿交通股份有限公司 - 設計構想

## 三種設計方向

<response>
<idea>
**Design Movement**: 台灣都市交通系統美學 (Urban Transit Modernism)
**Core Principles**: 
1. 清晰的資訊層級，讓乘客快速找到所需資訊
2. 藍白色系呼應公共交通的信任感與專業感
3. 卡片式佈局模仿公車路線牌的視覺語言
4. 粗體字型搭配細節排版，強調重要資訊

**Color Philosophy**: 深海藍 (#1B4F8A) 作為主色，象徵可靠與穩定；亮藍 (#2E86DE) 作為強調色；白色背景確保可讀性；橙黃色 (#F39C12) 用於警示與重要消息。

**Layout Paradigm**: 非對稱側邊導航 + 內容區域，首頁採用全寬英雄區塊搭配斜切設計，路線卡片採用網格佈局模仿公車時刻表。

**Signature Elements**: 
1. 路線號碼圓形徽章（模仿真實公車路線牌）
2. 斜切分隔線（呼應道路與交叉口）
3. 動態滾動消息跑馬燈

**Interaction Philosophy**: 懸停時路線卡片輕微上浮，消息列表有滑入動畫，導航列滾動後固定並加深背景。

**Animation**: 頁面載入時元素由下往上淡入；路線卡片懸停時有 translateY(-4px) 效果；消息列表使用 stagger 動畫依序顯示。

**Typography System**: 標題使用 Noto Sans TC Bold (900)，正文使用 Noto Sans TC Regular (400)，路線號碼使用等寬字型 Source Code Pro。
</idea>
<text>都市交通現代主義 - 藍白色系，卡片式路線佈局，強調資訊層級</text>
<probability>0.08</probability>
</response>

<response>
<idea>
**Design Movement**: 台灣公路風情 (Taiwan Highway Aesthetic)
**Core Principles**:
1. 以深色背景搭配高對比文字，模仿夜間公路的視覺感受
2. 綠色與白色的路標配色系統
3. 橫向滾動的路線展示，模仿公路里程碑
4. 大型數字與粗體字型強調路線編號

**Color Philosophy**: 深炭灰 (#1A1A2E) 背景，公路綠 (#16A085) 主色，白色文字，黃色警示線 (#F1C40F) 作為裝飾元素。

**Layout Paradigm**: 全螢幕英雄區塊 + 水平滾動路線展示 + 垂直消息流，採用不規則網格佈局。

**Signature Elements**:
1. 公路標誌風格的路線牌（六角形或盾形）
2. 虛線分隔線（模仿道路中線）
3. 里程碑式的時間軸消息

**Interaction Philosophy**: 路線牌懸停時有公路標誌的翻轉效果，消息時間軸有展開動畫。

**Animation**: 進場時模仿車輛行駛的水平滑入；路線卡片有 3D 翻轉效果；消息條目有打字機效果。

**Typography System**: 標題使用 Oswald Bold，正文使用 Noto Sans TC，路線號碼使用 Bebas Neue。
</idea>
<text>台灣公路風情 - 深色背景，公路標誌美學，高對比設計</text>
<probability>0.06</probability>
</response>

<response>
<idea>
**Design Movement**: 現代台灣公共服務設計 (Modern Taiwan Public Service Design)
**Core Principles**:
1. 乾淨、專業的政府服務網站美學，但加入現代感
2. 以藍色為主的色彩系統，搭配清晰的資訊架構
3. 卡片式設計語言，易於掃描與閱讀
4. 響應式設計，確保手機用戶的良好體驗

**Color Philosophy**: 台灣藍 (#003F88) 作為品牌主色，天空藍 (#4A90D9) 作為輔助色，淺灰 (#F5F7FA) 背景，深灰 (#2C3E50) 文字。

**Layout Paradigm**: 固定頂部導航 + 全寬英雄區塊 + 三欄資訊卡片 + 側邊欄消息列表，採用清晰的垂直節奏。

**Signature Elements**:
1. 路線號碼藍色圓形標籤
2. 漸層藍色英雄區塊
3. 帶有左側彩色邊框的消息卡片

**Interaction Philosophy**: 平滑滾動，卡片懸停有輕微陰影加深，按鈕有波紋效果。

**Animation**: 頁面元素 fade-in-up 動畫，導航列滾動後有背景模糊效果，路線卡片有 scale 微動畫。

**Typography System**: 標題使用 Noto Sans TC Black，副標題使用 Noto Sans TC Bold，正文使用 Noto Sans TC Regular。
</idea>
<text>現代台灣公共服務設計 - 藍色品牌，清晰資訊架構，現代感政府網站</text>
<probability>0.09</probability>
</response>

## 選定方向

選擇**方向一：台灣都市交通系統美學**，以深海藍為主色調，搭配卡片式路線佈局，強調資訊層級與公共交通的專業感。
