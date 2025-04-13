例）linux_basic_commands.md という名前のファイルをこの docker-practice リポジトリに追加する方法
GitHub Desktop または GitHubのWebページ どちらからでも可能。

✅ GitHub Desktopを使う場合
GitHub Desktopを開く
パソコンで GitHub Desktop を起動
リポジトリを選択
左上のリストから docker-practice を選ぶ
ローカルフォルダを開く
メニューの「Repository」→「Finderで表示（Mac）」または「Explorerで表示（Windows）」をクリックしてフォルダを開く
ファイルを作成（Macの場合はターミナルでtouchコマンド）
フォルダ内で linux_basic_commands.md という名前のファイルを作成して、Linuxの学習内容を入力
GitHub Desktopに戻る
自動で変更が反映され、「Changes」タブにファイルが表示される
コミットする
「コミットメッセージ」に add Linux basic commands などと入力して、「Commit to main」をクリック
GitHubにアップロード
右上の「Push origin」をクリックしてGitHubにアップロード

例）コマンド

cd /path/to/docker-practice

mkdir -p Docker/1_Basics
mkdir -p Docker/2_Dockerfile
mkdir -p Docker/3_DockerCompose

touch Docker/1_Basics/basics.md
touch Docker/2_Dockerfile/dockerfile.md
touch Docker/3_DockerCompose/docker_compose.md
→それぞれの .md ファイルに学習内容を Markdown で記述

✅ GitHubのWebページから追加する場合
リポジトリを開く
ブラウザで以下のURLを開く
https://github.com/kou-git-study/docker-practice
「Add file」→「Create new file」をクリック
ファイル名を入力
上部に linux_basic_commands.md と入力。
内容を入力
学習したLinuxコマンドをここに書き込む
下にスクロールして「Commit new file」ボタンを押す
