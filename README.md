# 食物功效搜尋系統

一個使用 Google Gemini 2.5 Flash 模型的智能食物功效分析網頁應用程式。

## 功能特色

- 🔍 **多食材搜尋**：支援同時輸入多種食物進行分析
- 💊 **功效分析**：詳細分析每種食物的營養價值和健康功效
- 🔗 **搭配分析**：分析多種食物一起食用的優缺點
- ⚠️ **注意事項**：提供食用建議和禁忌提醒
- 🎨 **現代化 UI**：美觀易用的使用者介面
- 📱 **完全獨立**：單一 HTML 檔案，無需伺服器，直接在瀏覽器開啟即可使用

## 使用方法

### 1. 取得 Gemini API Key

1. 前往 [Google AI Studio](https://makersuite.google.com/app/apikey)
2. 登入你的 Google 帳號
3. 點擊「Create API Key」建立新的 API Key
4. 複製 API Key

### 2. 開啟網頁

直接雙擊 `index.html` 檔案，或在瀏覽器中開啟 `index.html`

### 3. 輸入 API Key

首次使用時，在頁面上方的「Gemini API Key」欄位中輸入你的 API Key。API Key 會自動保存在瀏覽器本地，下次使用時會自動載入。

### 4. 搜尋食物功效

1. 在輸入框中輸入食物名稱
2. 可輸入多種食物，用逗號、換行或空格分隔
   - 例如：`蘋果、香蕉、菠菜`
   - 或：`番茄`（換行）`雞蛋`（換行）`牛奶`
3. 點擊「🔍 搜尋功效」按鈕
4. 系統會顯示：
   - 各食物的功效和營養成分
   - 一起食用的優點和協同效應
   - 一起食用時需要注意的缺點或禁忌
   - 食用建議

## 技術說明

- **前端**：純 HTML5 + CSS3 + JavaScript (Vanilla)
- **AI 模型**：Google Gemini 2.5 Flash (gemini-2.0-flash-exp)
- **API 調用**：使用 Google Generative AI JavaScript SDK（通過 CDN）
- **資料儲存**：API Key 保存在瀏覽器 localStorage

## 注意事項

- API Key 僅保存在你的瀏覽器本地，不會上傳到任何伺服器
- 請妥善保管你的 API Key，不要分享給他人
- API 調用可能需要一些時間，請耐心等待
- 建議的食用方式僅供參考，如有健康問題請諮詢專業醫師
- 某些瀏覽器可能因為 CORS 政策無法直接使用，建議使用 Chrome 或 Edge

## 授權

MIT License
