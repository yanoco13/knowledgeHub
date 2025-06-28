# KnowledgeHub

> Work / Dev ナレッジを素早く蓄積・検索できる個人向けWikiアプリ。

## ✨ Features
- Markdown でサクッと投稿
- タグ・フリーワード検索
- シンタックスハイライト対応
- ダークモード
- Firebase Auth によるログイン

## 🖥️ Tech Stack
| Category | Tech |
| -------- | ---- |
| Framework | Next.js 14 (App Router) |
| Language  | TypeScript |
| UI        | Tailwind CSS, shadcn/ui |
| Auth      | Firebase Auth |
| DB        | Firestore |
| Deploy    | Vercel |

## 🚀 Getting Started
```bash
# リポジトリをクローン
git clone https://github.com/yourname/knowledgehub.git
cd knowledgehub

# 依存関係をインストール
pnpm install  # または npm / yarn

# 環境変数を設定
cp .env.example .env.local
# .env.local を編集して Firebase 設定を入力

# 開発サーバ起動
pnpm dev
