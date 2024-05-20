# はじめに
## 準備
### 前提条件
以下が完了していることを確認してください。
- WindowsにGitがインストールされていること
  - [こちら](https://qiita.com/T-H9703EnAc/items/4fbe6593d42f9a844b1c)を参考にしてください。
- Githubのアカウントを作成していること
  
### リポジトリのクローン
すでにコラボレータ（=共同編集者）として登録されていることが確認できたら、  
Gitリポジトリのクローンを行いましょう。  
認証方法はHTTPSでOKです。

クローン先のディレクトリは「C:\work」にしておきましょう。  
「C:\work」を作成して、「C:\work」内でクローンしてください。
```
# コマンドプロンプトで以下のコマンドを実行してください
# Cドライブ直下に移動
cd C:\

# 「work」ディレクトリを作成
C:\>mkdir work

# git clone
git clone https://github.com/Mr-Kyary-at-eg/git_tutorial_with_n.git
```

(参考)  
https://docs.github.com/ja/repositories/creating-and-managing-repositories/cloning-a-repository

## 課題の取り組み方
分からないことは調べましょう。  
それでも分からなければ聞いてください。

# 課題
## 課題① developブランチを作成してPUSH
ローカルにてmainブランチから派生して、developブランチを作成しましょう。  
developブランチが作成できたら、PUSHしてください。

```
# mainブランチに移動
git checkout main

# developブランチを作成＆developブランチに移動
git checkout -b develop

# developブランチをリモートにPUSH
git push origin develop
```

（参考）  
https://qiita.com/yamaday0u/items/487c304ac63b693f4dfa

## 課題② Issueからタスクを実行
IssuesタブからIssueを確認してください。  


作業ブランチはfeature-001として、developブランチから派生すること。  
内容に沿った修正を行って、リモートへPUSH⇒プルリクエストを発行してください。  
レビュアーに狩野を設定してください。
