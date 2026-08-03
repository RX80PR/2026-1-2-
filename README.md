# 水曜1,2限 Web技術各論前期最終課題

## 手順書

### 1. リポジトリのクローンとディレクトリ移動

`git clone` でリポジトリをクローンし、設定ファイル（ `compose.yml` ）があるフォルダへ移動します。

```bash
git clone [https://github.com/RX80PR/2026-1-2-.git](https://github.com/RX80PR/2026-1-2-.git)
cd 2026-1-2-
```
# ※ 移動しないと compose.yml が見つからず起動エラーになるため。


### 2. Docker Compose で起動

以下のコマンドでアプリを起動する。

```bash
docker compose up
```
# ※ 初回起動時にテーブルの自動作成(init.sql の実行)が行われます。

### 3. アクセス

ブラウザから以下のURLにアクセスします。

```bash
http://[your-ip]/bbsimagetest.php
```

# ※ your-ip の部分は、ご自身の環境 (EC2のパブリックIPなど) に書き換えてください。i

