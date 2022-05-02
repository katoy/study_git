# Git の練習

## 概要

- hotfix
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

- <https://zenn.dev/t_sakurai/articles/174edae8b630c5>
  iPadでの開発環境を整える

- <https://news.mynavi.jp/techplus/article/20200520-1038925/>
  開発環境としてiPadを使う - ターミナルとSSHの利用がカギ

### git について

- <https://git-scm.com/book/ja/v2>
   Pro Git book 日本語版 オンライン

### docker + rails + vscode

- <https://weseek.co.jp/tech/2331/>
  VSCode × Docker で快適な開発環境をあなたにも

```text
tips
ファイルに直接、拡張機能の ID を入力できますが、以下の画像にあるように追加したい拡張機能を検索し、「 Add to devcontainer.json 」を選択することで自動で devcontainer.json の extensions に記述してくれます。
```

- <https://qiita.com/I_s/items/6faa45327e89ed1d6531>
  [VSCode]Remote Containersで開発環境を効率的に作成する

```text
VSCodeでcommand＋Shift＋Pを入力後、Remote-Containers: Add Development Container Configuration Filesと入力

その後は適当に最新版を選択後、OKを押下するとdevcontainer.jsonが作成されます
先程までなかった.devcontainerが作成されているはずなので、VSCodeでcommand＋Shift＋Pを入力後、Remote-Containers: Open Folder in Containerと入力
.devcontainerが存在するディレクトリでOKを押下
VSCodeが新規画面を開き、コンテナをビルドするのでしばらく待つ

extensions

VSCodeの拡張機能のIDを記載すれば、RemoteContainer起動時にコンテナ内に自動的にインストールされる
拡張機能のIDは拡張機能インストール画面で設定からコピー可能

自分のVSCodeで使用している拡張機能IDを一括で出力する場合のコマンド
code --list-extensions | xargs -L 1 echo code --install-extension

```

- <https://uncaughtexception.hatenablog.com/entry/2021/09/02/193132>
  Docker Desktop なしで VSCode の DevContainer を使う

- <https://madogiwa0124.hatenablog.com/entry/2022/01/30/173342>
  Ruby on Rails: 開発環境をVS CodeのRemote Containersで立ち上げるMEMO

- <https://qiita.com/haruhikonyan/items/b5b04c168d3f9de0e210>
  VSCode と devcontainer で作る Rails 開発環境

```shell
$ git clone https://github.com/haruhikonyan/rails-devcontainer -b rails6.1.0-and-mysql rails6.1.0-and-mysql
$ cd rails6.1.0-and-mysql
$ code .

vscode に terminal で ch /app してから
rails s -b 0.0.0.0
そのあと chrome で http:..localhost:3000 にアクセスする。
```

### vscode

- <https://qiita.com/otsuky/items/f46f5ee9eb11b3a9a4ba>
  VSCodeの拡張機能・設定を共有してチームみんなでエンジョイナイスDX

- <https://www.mitsue.co.jp/knowledge/blog/frontend/202108/30_1016.html>
  Visual Studio Codeの設定ファイルを共有してチーム開発をより快適にする

### rspec

- <https://www.miracleave.co.jp/contents/1487/rspec-shoulda-matchers/>
  RSpecをShoulda Matchersを使ってめちゃ簡単に書く
  