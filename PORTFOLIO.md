# 待辦清單 Web App

這是一個在 GitHub Copilot 實戰工作坊中完成的待辦清單 Web App。專案以簡潔的介面協助使用者新增、管理與清理日常待辦事項，並將資料保存在瀏覽器中。

## 線上展示

[GitHub Pages](https://ireneeee900119.github.io/my-copilot-workshop/)

## 功能

- 新增待辦事項。
- 輸入空白內容時不會新增項目。
- 勾選待辦事項並以刪除線與淡化樣式標示完成狀態。
- 刪除單筆待辦事項。
- 顯示整體未完成待辦事項數量。
- 清單為空時顯示提示文字。
- 使用 `localStorage` 保存待辦資料，重新整理後仍可保留。
- 一次清除所有已完成事項。
- 沒有已完成事項時停用「清除已完成」按鈕。
- 清除已完成事項前顯示瀏覽器內建確認對話框。
- 支援手機螢幕的響應式版面。

## 技術

- 使用純 HTML、CSS 與原生 JavaScript。
- 不使用框架、第三方套件或外部 CDN。
- 使用 CSS 變數管理介面顏色與共用樣式。
- 使用 `localStorage` 保存待辦資料。
- 使用 `textContent` 與 `createElement` 建立動態 DOM 內容。

## 開發方式

- 使用 GitHub Copilot Agent Mode，從需求逐步建立待辦清單 App。
- 使用 Microsoft Learn MCP 查詢官方文件，並使用 GitHub MCP 讀取 repository 的 Issue、推送分支與建立 Pull Request。
- 使用 `.github/prompts` 中的 `fix-issue.prompt.md` 建立 agentic workflow，依序完成讀取 Issue、提出計畫、等待確認、修改、驗證、提交、推送與建立 Pull Request。
- 透過 GitHub Issue 與 Pull Request 管理功能需求與修復流程。

## 我學到什麼

- 如何用原生 JavaScript 管理表單提交、待辦狀態與動態 DOM。
- 如何使用 `localStorage` 保存前端資料，讓頁面重新整理後仍能保留狀態。
- 如何將 GitHub Copilot Agent Mode 用於從需求到實作的開發流程。
- 如何設定與使用 MCP，讓 AI 能查詢官方文件並操作 GitHub 工作流程。
- 如何用 prompt 定義可重複執行、需要人工確認的 agentic workflow。
