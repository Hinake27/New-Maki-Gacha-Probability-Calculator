# 遊戲機率計算工具

一個簡單且實用的遊戲機率計算工具，支援多種伺服器的機率表格式，提供直觀的機率統計和分析功能。透過 Anthropic 的 Claude 3 Sonnet AI協助開發。

## 功能特點

### 主要功能
- 支援多種伺服器機率表格式（台服、韓服等）
- 自動計算總機率和分類統計
- 即時搜尋道具名稱
- 支援導出TXT格式的統計報告
- 自動識別並顯示顏色代碼（HEX、RGB）

### 支援格式
1. SABC等級格式（例如：`S等級特別的月光森林守護者服裝0.0820%`）
2. 一般格式（例如：`스페셜 프리렌의 의상0.1008%`）
3. 支援包含顏色代碼的道具名稱（例如：`髮型指定染色劑(螢光藍)#0000C0`）

## 使用說明

### 基本使用
1. 開啟遊戲官網機率表頁面
2. 直接用滑鼠圈選整個機率表（不需要排版）
3. 複製機率表（Ctrl+C）
4. 貼到工具的文字框中（Ctrl+V）
5. 點擊「計算機率」按鈕

### 進階功能
- **搜尋功能**：在搜尋框輸入關鍵字即時過濾道具
- **導出功能**：點擊「導出TXT檔案」保存完整統計報告
- **顏色預覽**：自動識別並顯示道具中的顏色代碼

## 顯示內容

### 機率統計
- 總機率計算
- 各等級機率統計
- 詳細機率列表

### 顏色道具
- HEX顏色碼
- RGB值
- 顏色預覽
- 道具完整資訊

## 技術說明

### 開發技術
- HTML5
- CSS3
- JavaScript（無需額外框架）
- Anthropic Claude 3 Sonnet（AI協助開發）

### AI 協作項目
- 程式碼優化建議
- 錯誤處理邏輯
- 正則表達式優化
- README文件撰寫
- 使用者介面改進建議

### 瀏覽器支援
- Chrome（推薦）
- Firefox
- Edge
- Safari

## 注意事項

1. 本工具僅供參考，實際機率以官方公告為準
2. 不同伺服器的機率表格式可能略有不同
3. 部分特殊格式可能需要手動調整

## 更新紀錄

### v1.0.0 (2024/03/22)
- 首次發布
- 基本機率計算功能
- 多語言支援
- 顏色代碼識別

### v1.1.0 (2024/03/23)
- 新增搜尋功能
- 新增導出功能
- 優化顯示介面
- 加入Claude AI協作開發

## 製作團隊

### 主要開發
- 製作者：Sorina
- 遊戲伺服器：台服
- 遊戲角色：愛麗沙

### AI協作
- AI模型：Claude 3 Sonnet
- 開發商：Anthropic
- 用途：程式碼優化與功能建議

## 回報問題

如發現任何問題或有功能建議，請聯繫製作者。

## 授權資訊

本工具僅供個人使用，禁止用於商業用途。

## 特別感謝

特別感謝 Anthropic 提供的 Claude AI 協助本項目的開發。Claude在以下方面提供了重要幫助：
1. 程式邏輯優化
2. 錯誤處理機制
3. 使用者介面設計建議
4. 文件撰寫協助
5. 跨語言支援實現
