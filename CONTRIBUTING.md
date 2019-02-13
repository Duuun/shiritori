# GitHubでやってみるしりとり

## 概要
- `GitHub flow` に慣れるためにGitHubでしりとりを行う。共同開発をするノリで

## 方法
- `master`ブランチにmdファイルをおく
  -  中身は過去のしりとりの一覧
  
```shiritori.md
## しりとり
- りんご
- ゴリラ
```

## チュートリアル
1. `git clone https://github.com/Duuun/shiritori.git`
2. `git checkout -b feature/hohogeo (update_shiritoriとかadd_wordとか)`
3. `README.md`を更新する。順番的に正しい次の言葉を下にかく
4. `git add .` `git commit -m "適当なコミットメッセージ"` `git push origin feature/update_hoghege`
5. GitHub上で`pull request`をだす
6. okだったらマージされる
7. Complete!! :100:
