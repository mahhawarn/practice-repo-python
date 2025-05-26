git fetch は、リモートリポジトリの最新の変更を取得するコマンドです。ただし、自分のローカルブランチには自動で反映されません。

1.変更内容を反映させる

cloneした時のローカルファイルの場所で最新のリポジトリの情報を読み込む。

```
git fetch
git pull origin main
```

2.README.md に2個目の解説を追記

任意のテキストエディタで README.md を開き、have.py の内容を変更し、何か関数を作成したら、その関数の解説を追加します。

3.変更したファイルをステージングしてコミット

編集したすべてのファイルをステージに追加し、コミットします。

```
git add .
git commit -m "Add example2 explanation to README"
```

4.リモートリポジトリに push

変更内容をリモートの main ブランチに反映させます。

```
git push origin main
```
