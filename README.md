# Jing's Cursor Rules

個人開發時常用的 [Cursor](https://www.cursor.com/) Rules 集合，涵蓋提交規範、程式碼風格、專案結構等，讓 AI 協作更一致、更高效。

## 使用方式

將需要的 `.mdc` 檔案複製到你專案的 `.cursor/rules/` 目錄下：

```bash
cp rules/commit-rules.mdc your-project/.cursor/rules/
```

或直接在 Cursor 的 Rules 設定中引用。

## 規則列表

| 檔案 | 說明 | 適用場景 |
|------|------|----------|
| [commit-rules.mdc](./rules/commit-rules.mdc) | Conventional Commits + Gitmoji 提交規範 | 所有專案 |

## 規則說明

### `commit-rules.mdc`

強制執行 Conventional Commits 格式搭配 Gitmoji，讓 commit 訊息清晰易讀。

格式：
```
<emoji> <type>(<scope>): <subject>
```

範例：
```
✨ feat(ui): add dark mode toggle
🐛 fix(api): handle null response from gemini
📝 docs(config): update deployment guide
```

## 貢獻

歡迎提交 PR 新增更多實用規則！
