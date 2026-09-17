# 拍立得小房間

獨立的拍立得邊框小工具。瀏覽器直接開就能用，不必安裝、不必建置。

## 上傳 GitHub Pages

保留這個資料夾的相對路徑，至少要有：

- `index.html`
- `manifest.webmanifest`、`sw.js`
- `icon-192.png`、`icon-512.png`、`icon-512-maskable.png`、`apple-touch-icon.png`
- `fonts/`、`vendor/`

把整個資料夾內容放到 Pages 來源（repo 根目錄或 `docs/`）。

本機預覽：

```bash
npx --yes serve .
```

也可以直接用瀏覽器開 `index.html`（`file://` 可用；Service Worker 只在 HTTP 下會註冊）。

## 功能

- 一次最多 20 張
- 邊框：白框、黑框、取色、復古、底片
- 比例：原圖、Mini、方框、Wide、橫幅、Instagram 貼文、限時動態
- 拖曳裁切，雙指或滾輪縮放
- EXIF 自動帶入相機資料（不改寫原檔）
- 單張下載／分享，多張打包 ZIP

## 主題

右上角可切換：工作桌、太空、日式、中式、像素、科幻、OLED 全黑。選擇會記在瀏覽器裡。
