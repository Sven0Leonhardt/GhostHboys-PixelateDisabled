需一併安裝的檔案：
- GhostHboys-PixelateDisabled-Test.pak
- GhostHboys-PixelateDisabled-Test.ucas
- GhostHboys-PixelateDisabled-Test.utoc

安裝方法：
1. 關閉遊戲。
2. 將上述三個檔案複製到 `GhostHboys/Content/Paks` 目錄下。
3. 啟動遊戲，並前往包含像素化效果的場景進行確認。

修改內容：
- 僅覆寫 `/Game/ChromaShaders/Materials/MI_Pixelate_Selected`。
- 保留原始父材質 `M_Pixelate_Selected`。
- 將「像素化縮放」（Pixelation Scale）參數值從約 14.55725 修改為 1.0。
- 保持「效果距離」（Effect Distance）參數不變（約 3091.6355）。
- 不會修改遊戲原有的資源包（containers）、存檔或語言補丁。

卸載方法：
1. 關閉遊戲。
2. 從 `Paks` 目錄中刪除那三個 `GhostHboys-PixelateDisabled-Test` 檔案。

該資源包已通過 `retoc verify` 驗證。在維護者的遊戲環境中測試通過；若使用其他遊戲版本或配置，實際效果可能有所不同。


Files to share and install together:
- GhostHboys-PixelateDisabled-Test.pak
- GhostHboys-PixelateDisabled-Test.ucas
- GhostHboys-PixelateDisabled-Test.utoc

Install:
1. Close the game.
2. Copy all three files into GhostHboys/Content/Paks.
3. Start the game and check the scene that uses the pixelation effect.

What this changes:
- Overrides /Game/ChromaShaders/Materials/MI_Pixelate_Selected only.
- Keeps the original parent material M_Pixelate_Selected.
- Changes the Pixelation Scale scalar from about 14.55725 to 1.0.
- Keeps Effect Distance unchanged at about 3091.6355.
- Does not modify the original game containers, saves, or language patch.


Uninstall:
1. Close the game.
2. Delete the three GhostHboys-PixelateDisabled-Test files from Paks.

The container was verified with retoc verify. Tested successfully in the
maintainer's game setup; other game versions or configurations may differ.


【授權與免責聲明】
• 版權歸屬：本補丁不享有原檔案（原作品）之智慧財產權，原著作權仍歸原作者或原發行公司所有。
• 自由分享：歡迎自由複製、修改與散布本補丁內容。
• 禁止商用：嚴禁將本補丁用於任何商業用途、營利行為或進行販售。


[Authorization and Disclaimer]
• Copyright Ownership: This patch does not grant any intellectual property rights over the original files (the original work); all such rights remain with the original author(s) or the original publisher(s).
• Free Sharing: You are free to copy, modify, and distribute the contents of this patch.
• Non-Commercial Use: The use of this patch for any commercial purpose, profit-seeking activity, or sale is strictly prohibited.
