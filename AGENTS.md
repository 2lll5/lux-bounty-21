# Agent Instructions

## Google Drive Build 交付規範（所有 Agent 必須遵守）
- **專案同名資料夾**：所有已完成、可執行且經驗證的 Build 請送至 Google Drive `AI Project/lux-bounty-21/`（AI Project ID: `1Yhfro6Ss5TSCXCVIZIHEu5h7V1gL8b27`）；不可在 `AI Project/` 根目錄散放檔案，或每次 Build 在頂層建立版本資料夾。
- **最新版放專案根目錄**：ZIP／EXE、對應 SHA-256、完整分割檔、還原腳本與安裝說明要放在一起。不同平台的完整最新版可以並存。檢查版本、上傳後的檔名／parent／大小／checksum；只有 checksum、缺 ZIP 或缺分割檔的版本不完整，**不得取代前一完整版本**。
- **重大差異才另設版本子資料夾**：重要功能、架構、相容性或美術里程碑可保存於 `vX.Y.Z-說明/`；普通舊版非破壞性移入 `歷史封存/`，不刪除。
- 每次新開發提交 GitHub；昂貴 Build／發布 Actions 僅在必要 `workflow_dispatch` 或正式 `release: published`，避免每次推 main 都觸發。未驗證成功不得宣稱已 Build／上傳；回報版本、資料夾連結、檔案與校驗結果。
**Coding agent English:** Keep newest complete verified builds directly in `AI Project/lux-bounty-21/`; preserve milestone versions only for significant differences; archive older routine builds without deletion.
