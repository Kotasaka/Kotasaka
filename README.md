## nodenvによるバージョン管理

```bash
# nodenvのインストール
brew install nodenv

# nodeのインストール (18.10.0)
nodenv install 18.10.0

# バージョンの指定
# ディレクトリごと
nodenv local 18.10.0

# 全体に適用
nodenv global 18.10.0
```

`.node-version`にバージョン管理している
## サーバーの起動

サーバーの起動
```bash
npm run dev
```

[http://localhost:3000](http://localhost:3000)

↑にアクセスすると`pages/index.js`にある画面が表示される。
