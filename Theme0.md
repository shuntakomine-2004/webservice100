#00.Gitのインストールとバージョン確認
実行結果
komineshunta@komineshuntanoMacBook-Air webservice100 % git --version
git version 2.46.0

#01. リポジトリの初期化と最初のコミット
git add README.md

git commit
[master (root-commit) b00e584] Add README file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

git log
commit b00e58472eeb50de8cb7b647bb260b6c87fcb233 (HEAD -> master)
Author: Shunta Komine <komine.shunta.2004@gmail.com>
Date:   Tue Oct 7 11:30:25 2025 +0900

    Add README file

#02. GitHubアカウントの作成とSSHキー登録
ssh -T git@github.com
Hi shuntakomine-2004! You've successfully authenticated, but GitHub does not provide shell access.

#03. ローカルリポジトリとGitHubリポジトリの連携
git remote -v
origin  git@github.com:komineshunta/webservice100.git (fetch)
origin  git@github.com:komineshunta/webservice100.git (push)

#04. ファイルの変更とpush/pull
github上で変更

#05. .gitignoreファイルの作成

<img width="337" height="95" alt="Screenshot 2025-10-28 at 11 11 24" src="https://github.com/user-attachments/assets/ed597208-ecae-4f75-a102-9f4860d680be" />

.gitignore ファイル: node_modules

git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean


#06. ブランチの作成と切り替え
git branch

* develop
  main
