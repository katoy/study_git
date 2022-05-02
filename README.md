# Git の練習

## 概要

- hofix
- hotfix2
- git merge --ammend

## 付録

## 引用

### 参考

- <https://errorshare.dev/articles/3f63f049-2a5d-438f-b459-91cf4b9b0d09>
git pullした時に出るエラー

```text
You have divergent branches and need to specify how to reconcile them
-->
git config --global pull.rebase false
```

### for Ipad

- <https://blogchroma.com/programming/programming-env/codeserver_with_ipad_intro/>
  【code-server】iPadでコーディングできるようにする

- <https://qiita.com/YKIYOLO/items/06cf44dead84188677ae>
  Dockerでcode-serverを立てる

- <https://zenn.dev/iamsmith/articles/16e30984bfa0f3>
  コンテナでcode-serverを動かす

- https://zenn.dev/t_sakurai/articles/174edae8b630c5
  iPadでの開発環境を整える

- <https://news.mynavi.jp/techplus/article/20200520-1038925/>
  開発環境としてiPadを使う - ターミナルとSSHの利用がカギ

### git について

- <https://git-scm.com/book/ja/v2>
   Pro Git book 日本語版 オンライン

### docker + rails + vscode

- <https://madogiwa0124.hatenablog.com/entry/2022/01/30/173342>
  Ruby on Rails: 開発環境をVS CodeのRemote Containersで立ち上げるMEMO

- https://qiita.com/haruhikonyan/items/b5b04c168d3f9de0e210
  VSCode と devcontainer で作る Rails 開発環境

```shell
$ git clone https://github.com/haruhikonyan/rails-devcontainer -b rails6.1.0-and-mysql rails6.1.0-and-mysql
$ cd rails6.1.0-and-mysql
$ code .

vscode に termilal で ch /app してから
rails s -b 0.0.0.0
そのあと chrome で http:..localhost:3000 にアクセスする。
```
