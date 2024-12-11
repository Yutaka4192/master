# master
git add ファイル名
git commit -m コメント

# リポジトリに登録
git push origin master

# リポジトリから取得
git pull origin master
git clone https://github.com/Yutaka4192/master.git

以下のコマンドで、gitサーバへのパスワードを記憶させることができ、都度パスワード入力しなくて済むようになる。
git config credential.helper store
