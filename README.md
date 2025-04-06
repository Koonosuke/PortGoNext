# Next.js × Go(Echo) × AWS S3　Portfolio

このポートフォリオは、**Go（Echo）** をバックエンド、**Next.js（App Router）** をフロントエンドに採用し、**JWT認証 + ユーザーコンテキスト管理**で作成したポートフォリオサイトです。

---

##  特徴

-  **JWTによるログイン認証**（`localStorage`にトークン保存）
- **ユーザーコンテキストのグローバル管理**（`UserContext`でログイン状態を管理）
- **プロフィールアイコンのアップロード**（S3アップロード対応）
- **Experience / CareerのCRUD管理**
- **フロントはNext.js + Tailwind CSSでレスポンシブ対応**
- **スマホ・PC対応**
-  デプロイ済み：https://nextdeploy-navy.vercel.app/
  - フロント： [Vercel](https://vercel.com/)
  - バックエンド： [Render](https://render.com/)
  - データベース： PostgreSQL（Render）

---

## 使用技術スタック

### フロントエンド
- `Next.js`（App Router / Client Components）
- `TypeScript`
- `Tailwind CSS`
- `Framer Motion`
- `React Context API`

### バックエンド
- `Go（Echoフレームワーク）`
- `JWT認証`
- `PostgreSQL`
- `GORM`
- `AWS S3`（アイコンアップロード）

---


