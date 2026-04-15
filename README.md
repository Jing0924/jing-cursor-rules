# Jing's Cursor Rules

個人開發時常用的 [Cursor](https://www.cursor.com/) Rules 集合，依技術類別分資料夾管理，讓 AI 協作更一致、更高效。

## 使用方式

將需要的 `.mdc` 檔案複製到你專案的 `.cursor/rules/` 目錄下：

```bash
cp commit/commit-rules.mdc your-project/.cursor/rules/
cp nextjs/nextjs.mdc your-project/.cursor/rules/
```

## 目錄結構

```
jing-cursor-rules/
├── commit/          # Git 提交規範
└── nextjs/          # Next.js 相關規則
```

## 規則列表

### `commit/`

| 檔案 | 說明 |
|------|------|
| [commit-rules.mdc](./commit/commit-rules.mdc) | Conventional Commits + Gitmoji 提交規範，含 emoji 類型對照表與 AI 指導語 |

### `nextjs/`

| 檔案 | 說明 |
|------|------|
| [nextjs.mdc](./nextjs/nextjs.mdc) | TypeScript + Next.js App Router + Shadcn UI + Tailwind 通用最佳實踐 |
| [nextjs-react-generalist-cursor-rules.mdc](./nextjs/nextjs-react-generalist-cursor-rules.mdc) | 全端通才規則，涵蓋 JS/TS/CSS/React/Next.js |
| [nextjs-react-typescript-cursor-rules.mdc](./nextjs/nextjs-react-typescript-cursor-rules.mdc) | React + TypeScript + Next.js App Router 嚴謹規範 |
| [nextjs-react-redux-typescript-cursor-rules.mdc](./nextjs/nextjs-react-redux-typescript-cursor-rules.mdc) | React + Redux + TypeScript + Next.js 完整開發規範 |
| [nextjs-react-vite-javascript-cursor-rules.mdc](./nextjs/nextjs-react-vite-javascript-cursor-rules.mdc) | React + Vite + JavaScript + Zustand + Shadcn UI |
| [nextjs-typescript-tailwindcss-supabase-cursor-rules.mdc](./nextjs/nextjs-typescript-tailwindcss-supabase-cursor-rules.mdc) | Next.js + TypeScript + Tailwind + Supabase 全端規範 |
| [nextjs-vite-solidity-typescript-cursor-rules.mdc](./nextjs/nextjs-vite-solidity-typescript-cursor-rules.mdc) | Next.js + Solidity + Wagmi + Viem Web3 開發規範 |
| [optimized-nextjs-typescript-best-practices-modern-ui-ux.mdc](./nextjs/optimized-nextjs-typescript-best-practices-modern-ui-ux.mdc) | 最佳化 Next.js + TypeScript，強調 Clean Code 與現代 UI/UX |
| [payload-cms-nextjs-typescript-best-practices.mdc](./nextjs/payload-cms-nextjs-typescript-best-practices.mdc) | Payload CMS + Next.js + TypeScript + MongoDB 全端規範 |
| [blog-glass-design-system.mdc](./nextjs/blog-glass-design-system.mdc) | Glassmorphism 設計系統規格書，定義配色 Token 與卡片變體 |
| [nextjs-tailwind-glassmorphism.mdc](./nextjs/nextjs-tailwind-glassmorphism.mdc) | Next.js + Tailwind Glassmorphism 視覺風格規則 |

## 貢獻

歡迎提交 PR 新增更多實用規則！
