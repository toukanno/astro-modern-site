# astro-modern-site

モダンなランディングページ用の Astro 5 スターターです。

## 技術スタック

- [Astro](https://astro.build/) 5.5
- 静的サイト生成 (SSG)

## セットアップ

```bash
npm install
```

## 開発

```bash
npm run dev
```

開発サーバーが起動します（デフォルト: http://localhost:4321）。

## ビルド

```bash
npm run build
```

静的ファイルが `dist/` に出力されます。

## テスト

自動テストは未実装です。最低限の動作確認として、次のビルドを成功させてください。

```bash
npm run build
```

## プレビュー

```bash
npm run preview
```

ビルド済みサイトをローカルでプレビューします。

## ディレクトリ構成

```
astro-modern-site/
├── public/          # 静的アセット
├── src/
│   ├── layouts/     # レイアウトコンポーネント
│   └── pages/       # ページ（ファイルベースルーティング）
└── package.json
```

## 公開先候補

- GitHub Pages
- Cloudflare Pages
- Vercel
- Netlify

## Development Rules

- [AGENTS.md](./AGENTS.md) — Sub-agent configuration for Claude Code / Codex
- Commits must pass CI before merging to main
- Use feature branches + pull requests for all changes
