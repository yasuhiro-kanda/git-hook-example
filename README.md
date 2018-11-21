README.md


```sh
$ cd /path/to/temp
$ git checkout https://github.com/yasuhiro-kanda/git-hook-example.git
$ cd git-hook-example
$ git checkout -b example
$ touch example.txt
$ git add ./
$ git commit -m 'add example.txt'
$ git checkout master
$ git merge master example
$ ls ./txt
(リポジトリルート直下に追加した example.txt が git-mv によって ./txt ディレクトリ以下にあるのを確認)
```