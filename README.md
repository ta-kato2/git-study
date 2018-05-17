## Gitとは
- 分散型のオブジェクトDB

## 分散型とは
- SVN・・・中央型
- Git、mercurial等・・・分散型
- マスターリポジトリは存在せず、それぞれのローカルリポジトリがあるだけ

## 基本的なコマンド（ローカル完結編）
- git init
- git add
- git commit
- git branch
- git log

SHA1で参照を管理しているオブジェクトDBです。

## 便利なエイリアスを設定しておく
- bash_profileをいじろう！

## 基本的なコマンド（巻き戻し・ヘッダー移動系）
自分がいまどこにいるのかを意識する。

- git reset (HEAD)
- git reset --hard
- git checkout (HEAD or commit id)

## 他のリポジトリとの同期・連携
ローカルリポジトリ、ローカルワーキングスペース、リモートリポジトリを意識する必要がある。
- git clone
- git remote add
- git push
- git fetch
- git pull

## ブランチのマージ
- git merge
　　・fast-foward
　　・no-fast-foward
- git merge —rebase
- git merge --squash

## ちょっと特殊系
- git stash (pop)
- git blame
- git reflog

## Githubの使い方
- Gitフロー・Githubフロー
- WIPでPR作成
- レビュー
　　・nit, LGTM…etc
　　・動作確認は最低限やってから出そう
　　・完成していなくても、相談のためのレビューとかもありだよ
- Forkで運用するパターン（複数のリモートリポジトリ）
