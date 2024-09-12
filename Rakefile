## 目次

1. [プロジェクトについて](#プロジェクトについて)
2. [環境](#環境)
3. [開発環境構築](#開発環境構築)

## プロジェクトについて
Railsアプリケーション のテンプレート

## 環境
| 言語・フレームワーク  | バージョン |
| --------------------- | ---------- |
| ruby                  | 3.2.2      |
| rails                 | 7.0.8      |
| postgresql            | 12         |

## 開発環境構築
### リポジトリのクローン
```
git clone https://github.com/kei-shibainu/rails-docker.git
```

### dockerイメージのビルド
```
docker compose up --build -d
```

### コンテナ内に移動
```
docker compose exec web bash
```

### データベースの作成及びマイグレーションの実施
```
rails db:create
rails db:migrate
```

### アプリケーションの起動確認
`http://localhost:3000` にアクセスする。
