# PearlCue Updates

## 專案整理卡

- 用途：PearlCue 的公開更新倉庫，保存 latest release artifacts 與 Tauri updater metadata。
- 可見性：public。
- 分類：公開展示，優先級 B。
- 目前狀態：公開支援 repo。內容應精簡，只服務 updater 與使用者下載。
- 下次打開先讀：先確認 latest release、`latest.json` 與 README。
- 最小驗證：每次發版後確認 latest release 可公開下載，`latest.json` 指向正確 artifact。
- 風險邊界：不要把 PearlCue 主程式私有內容、私鑰或內部發版筆記放進此公開 repo。
- 下一步：下次補最小 release 操作備忘，避免更新 repo 被誤當主程式 repo。


Public release artifacts and Tauri updater metadata for PearlCue.

This repository intentionally stores installer assets and latest.json only. Source code stays in the main PearlCue repository.
