# master
git add ファイル名
git commit -m コメント

# リポジトリに登録
git push origin master

# リポジトリから取得
git pull origin master
git clone https://github.com/Yutaka4192/master.git

.git/config
[remote "origin"]
url = https://{GitHubユーザー名}:{GitHubトークン}@github.com/{リポジトリURL}

以下のコマンドで、github.comへのパスワードを記憶させることができ、都度パスワード入力しなくて済むようになります。
git config credential.helper store
