# 床邊故事 Web App

這是一個簡單的床邊故事 Web 應用程式，適合兒童閱讀和聆聽故事。應用程式會自動朗讀每個故事，並每10秒自動切換到下一個故事。所有故事和圖片都存儲在本地端。

## 功能

- 自動朗讀故事
- 每10秒自動切換到下一個故事
- 響應式設計，適應不同的設備螢幕大小

## 安裝和運行

### 前置需求

- 網頁瀏覽器
- Python 3.x

### 步驟

1. 克隆這個倉庫到你的本地端：
    ```bash
    git clone https://github.com/你的用戶名/床邊故事.git
    ```

2. 進入專案目錄：
    ```bash
    cd 床邊故事
    ```

3. 
   啟動本地 HTTP 伺服器 ：
    ```bash
    python3 -m http.server
    ```
- Ｗindows 用戶可以直接打開 start_server.bat
- Mac/Linux 用戶可以直接打開 start_server.sh
  

4. 在瀏覽器中打開以下網址：
    ```
    http://localhost:8000
    ```

## 文件結構

- `index.html`: 主 HTML 文件，包含應用程式的結構和邏輯。
- `bedtimestories.json`: 儲存所有故事文本和圖片的 JSON 文件。
- `images/`: 儲存所有故事圖片的目錄。
- `start_server.sh`: 啟動本地 HTTP 伺服器的 Shell 腳本。

## 使用說明

1. 開啟應用程式後，故事會自動開始朗讀並每10秒切換到下一個故事。
2. 可以使用「朗讀故事」按鈕重新開始當前故事的朗讀。
3. 可以使用「停止」按鈕停止當前故事的朗讀。
4. 可以使用「下一個故事」按鈕手動切換到下一個故事。

## 貢獻

歡迎提交問題或請求合併。如果你有任何改進或新功能的建議，請隨時提交 pull request。

## 授權

這個專案使用 MIT 授權。