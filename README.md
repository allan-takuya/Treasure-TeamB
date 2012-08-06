# README

gitのコマンドまとめ
=================

### Gitリポジトリの作成
    git init

### ステージへのファイルの追加
    git add file_name

### コミット
    git commit -m 'commit_message'

### リモートリポジトリの追加
    git remote add remote_name repository_path

### リモートリポジトリへの変更の反映
    git push -u remote_name branch_name

### リモートリポジトリの変更状態の取得
    git fetch remote_name

### リモートリポジトリでの変更を取り込む
    git pull --rebase remote_name branch_name

### 既存のリポジトリのClone
    git clone repository_path

### ローカルリポジトリの状態確認
    git status

### ブランチの作成
    git branch new_branch_name

### ブランチの切り替え
    git checkout branch_name

## ブランチの作成と切り替え
    git checkout -b new_branch_name
    
### ブランチの一覧(リモートブランチを含む）
    git branch -a

### ブランチの一覧(リモートブランチを含まない）
    git branch
