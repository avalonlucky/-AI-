# QR Code 工具

編碼與解碼一體完成的網頁工具，採用 Claude 風格簡潔介面。

## 功能

### 生成 QR Code
- 輸入網址，一鍵生成 QR Code
- 支援完整 URL 或簡短格式（自動補上 `https://`）
- **自定義 PNG 尺寸**：64px～2048px 任意設定
- 下載 SVG 矢量格式，可無限縮放

### 上傳解碼
- 上傳 QR Code 圖片或拖曳至方框內
- 即時解碼並顯示內容
- 若為網址則可點擊開啟

## 使用方式

1. 用瀏覽器開啟 `index.html`（建議使用本地伺服器）
2. **生成**：輸入網址 → 生成 → 設定尺寸 → 下載 PNG 或 SVG
3. **解碼**：點擊「上傳解碼」或拖曳圖片至方框

## 技術

- 純前端實現，無需伺服器
- 生成：[qrcode](https://github.com/soldair/node-qrcode)
- 解碼：[jsQR](https://github.com/cozmo/jsQR)
