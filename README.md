

# 在 macOS 與 Windows 上實現標楷體的有效互通解決方案

「標楷體」是一款常見的中文字型，但在 macOS 與 Windows 之間由於預裝版本差異，經常導致跨平台文件顯示不一致。本指南提供了一個簡單且可靠的解決方案，通過統一安裝特定的「標楷體」字型文件（`kaiu.ttf`），確保在 macOS 與 Windows 上均能正確顯示與編輯文件。

## 安裝步驟

### Step 1: 關閉文件編輯器
在開始安裝前，請關閉所有正在使用的文件編輯器（如 Word、Excel、PowerPoint 等），以避免字型載入衝突。

> **備註**：若不方便立即關閉，可在字型安裝完成後重新啟動應用程式以載入新字型。

---

### Step 2: 開啟 macOS 字體簿
1. 在鍵盤上按下 `Command + Space` 開啟 Spotlight 搜尋。
2. 輸入「字體簿」（Font Book），並按 Enter 鍵進入字體管理工具。

---

### Step 3: 停用 macOS 預裝標楷體
1. 在「字體簿」中，找到以下字型：
   - 「標楷體-繁」
   - 「標楷體-港澳」
2. 對每個字型點選右鍵，選擇「停用」或「移除」選項。
   - **建議**：選擇「停用」而非「移除」，以保留系統預設字型作為備用。

> **注意**：此步驟確保 macOS 使用我們即將安裝的統一字型，避免系統預設字型版本衝突。

---

### Step 4: 下載標楷體字型檔案
1. 前往以下 GitHub Gist 連結下載字型文件：
   - [kaiu.ttf](https://gist.github.com/irwincong/21a04035e41813d7d5f56552b9a983de)
2. 點擊「Download」按鈕，將 `kaiu.ttf` 保存至本地電腦。

> 來源說明：此 `kaiu.ttf` 字型檔案由 GitHub Gist 用戶分享，宣稱針對跨平台顯示相容性進行優化。建議使用前先行測試其在目標系統上的顯示效果，並留意相關授權條款。

---

### Step 5: 安裝字型
#### 在 macOS 上
1. 找到下載的 `kaiu.ttf` 文件，解壓縮（如為壓縮檔）。
2. 雙擊 `kaiu.ttf`，系統將自動開啟「字體簿」。
3. 在「字體簿」中點擊「安裝字體」按鈕完成安裝。

---

### Step 6: 驗證安裝
1. 開啟文件編輯器（如 Microsoft Word）。
2. 在字型選單中找到「標楷體」，並測試輸入文字。
3. 將文件儲存並傳送至另一平台（macOS 或 Windows），確認字型顯示正常。

完成以上步驟後，無論是在 macOS 或 Windows 上開啟文件，或將文件分享給他人，「標楷體」均能一致顯示，不會出現亂碼或字型替換問題。

---

## 注意事項
- 若文件仍無法正確顯示，請確認雙方系統均已安裝相同的 `kaiu.ttf` 文件。
- 在 macOS 上停用預設字型後，若需恢復，可在「字體簿」中重新啟用「標楷體-繁」或「標楷體-港澳」。
- 下載字型時，請確保來源可靠，避免使用未經驗證的文件。

---

## 常見問題 (FAQ)
**Q: 為什麼需要停用 macOS 的預設標楷體？**  
A: macOS 預裝的「標楷體-繁」與 Windows 的標楷體版本不同，停用後使用統一的 `kaiu.ttf` 可確保跨平台一致性。

**Q: Windows 用戶需要額外步驟嗎？**  
A: 不需要，Windows 用戶無需停用任何預設字型。

---

希望這篇指南符合您的需求！
