# Firefox NewTab Dark Wallpaper

Force Firefox new tab to always use dark color scheme with wallpapers, bypassing `lightWallpaper` class styling via `userContent.css`.

> 強制 Firefox 新分頁在使用桌布時套用深色配色方案，透過 userContent.css 覆寫 lightWallpaper 樣式

---

## Problem / 問題

Firefox automatically applies `lightWallpaper` class to new tab page when using wallpapers, forcing light color scheme regardless of system preferences.

Firefox 在新分頁使用桌布時會自動套用 `lightWallpaper` class，強制使用淺色配色而忽略系統偏好設定。

---

## Installation Steps

1. **Locate your Firefox Profile folder**:
   - Type `about:support` in the address bar
   - Find "Profile Folder" (or "Profile Directory")
   - Click "Open Folder" (or "Open Directory")

2. **Create the `chrome` folder** (if it doesn't exist):
   - Create a folder named `chrome` inside your Profile folder

3. **Create `userContent.css`**:
   - Create a file named `userContent.css` inside the `chrome` folder
   - Copy the [CSS code](userContent.css) into this file

4. **Enable userContent.css** (if not already enabled):
   - Type `about:config` in the address bar
   - Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
   - Set it to `true`

5. **Restart Firefox** for the changes to take effect

---

## 設定步驟

1. **找到 Firefox Profile 資料夾**:
   - 在網址列輸入 `about:support`
   - 找到「設定檔資料夾」(Profile Folder)
   - 點擊「開啟資料夾」

2. **創建 `chrome` 資料夾** (如果不存在):
   - 在 Profile 資料夾中創建名為 `chrome` 的資料夾

3. **創建 `userContent.css`**:
   - 在 `chrome` 資料夾中創建 `userContent.css` 檔案
   - 複製 [CSS 代碼](userContent.css) 到此檔案

4. **啟用 userContent.css** (如果尚未啟用):
   - 在網址列輸入 `about:config`
   - 搜尋 `toolkit.legacyUserProfileCustomizations.stylesheets`
   - 設為 `true`

5. **重啟 Firefox** 讓設定生效

---

## Features / 特色

- ✅ Preserves `layout.css.prefers-color-scheme.content-override` setting / 保留系統配色偏好設定
- ✅ Works with all Firefox wallpapers / 適用於所有 Firefox 桌布
- ✅ No extension required / 無需安裝擴充功能
- ✅ Supports high contrast mode / 支援高對比模式

---

## Acknowledgments

- CSS solution generated with [Claude AI](https://claude.ai)
- Based on Firefox's `activity-stream.css` structure

## License

MIT
