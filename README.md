# Qiita CLIをdocker環境で使えるツール
## メリット
- ローカル環境で好きなエディタで書ける
- Qiita MDのプレビューが可能
- Gitを使えばGit管理できる

## 導入方法
### 前提条件
- Windows10に導入(他OS未確認)
- Docker Desktopが入ってる

## 手順
### 1. このリポジトリをクローン

### 2. Dockerコンテナを立てる
`docker/`下で以下のコマンド  
```
docker-compose up -d
```

### 3. Qiita のトークンを発行する
[こちらに手順]([https://qiita.com/Qiita/items/666e190490d0af90a92b#qiita-%E3%81%AE%E3%83%88%E3%83%BC%E3%82%AF%E3%83%B3%E3%82%92%E7%99%BA%E8%A1%8C%E3%81%99%E3%82%8B)

### 4. Qiita CLI のログイン
[参考](https://qiita.com/Qiita/items/666e190490d0af90a92b#qiita-cli-%E3%81%AE%E3%83%AD%E3%82%B0%E3%82%A4%E3%83%B3)

### 5. 記事を書いて投稿
`public/`下にmdファイル作っていきます。  
続きの使用方法は以下  
[記事投稿・操作等 参考](https://qiita.com/Qiita/items/666e190490d0af90a92b#qiita-preview-%E3%81%AE%E8%B5%B7%E5%8B%95%E3%83%97%E3%83%AC%E3%83%93%E3%83%A5%E3%83%BC%E7%94%BB%E9%9D%A2%E3%81%AE%E8%A1%A8%E7%A4%BA)
