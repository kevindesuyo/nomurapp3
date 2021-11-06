# 初期セットアップ

#　前提条件
- コマンドラインが開ける
- gitがインストールされている
- dockerがインストールされている
- docker-composeがインストールされている 



1. リポジトリのコピー
```
git clone https://github.com/kevindesuyo/nomurapp3
```
2.ディレクトリの移動
```
cd nomurapp
```

3. dockerコンテナを起動します。

```bash
docker-compose up --build -d
```

その後 http://localhost8000 に接続、多分これで動く