# How to use

まずは Franz をダウンロードし、インストール。アカウントを作成して、最初に仮で何かサービスを一つ追加する。

https://meetfranz.com/


Franz のフォルダに移動

````
$ cd ~/Library/Application\ Support/Franz/recipes/
````

ls でフォルダを確認してなければ dev　フォルダを作成し、移動する。

````
$ ls 
gmail	temp
$ mkdir dev
$ cd dev
````

heroku という名称で Clone

````
$ git clone https://github.com/chatbox-inc/franz-recipe-heroku heroku
Cloning into 'heroku'...
remote: Counting objects: 34, done.
remote: Compressing objects: 100% (16/16), done.
remote: Total 34 (delta 5), reused 20 (delta 4), pack-reused 13
Unpacking objects: 100% (34/34), done.
````

Cmd + Shift + R で　Franz を再起動し Cmd + N でサービスの追加を開くと、開発版が選択可能になるため、herokuを追加する。
