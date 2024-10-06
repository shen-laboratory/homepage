# 沈 研究室 ホームページ

## 編集の仕方

### 初回導入

1. github のアカウントを [このページ](https://github.co.jp/)の右上のサインアップで作製し、今のホームページの担当者に招待してもらってください。

    * 招待する担当者は [ココ](https://github.com/shen-laboratory) の画面上の「People」->「Invite member」から招待してください．

1. Visual Studio Code のインストール

[このリンク](https://code.visualstudio.com/download) から Visual Studio Code をインストールしてください。

2. Node のインストール

[このリンク](https://qiita.com/gahoh/items/8444da99a1f93b6493b4) から npm(node.js) をインストールしてください。

3. github からコードをコピーする

自分のパソコンで `Powershell` を開いて下のコマンドを実行する。

```bash
git clone https://github.com/gae-22/shen-lab.git
```

`git` がないと怒られた場合は [このページ](https://qiita.com/T-H9703EnAc/items/4fbe6593d42f9a844b1c) を参考に `git` をインストールしてください。

4. Visal Studio Code の astro拡張機能を インストールする。

5. 編集する環境を整える

    1. 以下のコマンドを実行して Visual Studio Code でこのコードを開く。

    ```bash
    code homepage
    ```
    2. 以下のコマンドを実行して Webサイトをプレビューできるようにする

    ```bash
    npm install -g astro
    npm install
    ```

### 次回以降
1. Visual Studio Code でこのコードを開く
2. `git pull origin main` して最新のコードを持ってくる
2. `npm run dev` を実行してプレビューを表示
3. 好きに編集する
4. 編集がひと段落して動作確認ができたら github に上げる
    1. git add .
    2. git commit -m "メッセージ"
    3. git push origin main

### 引き継ぐ場合(Owner 移行する場合)
1. github 画面上の Setting を押す。
2. 画面の下まで行き、Transfer ownership のtransfer を押す。
3. Specify an organization or username で引き継ぐ人のアカウント名を入力する。
4. 下の指示に従って、`<自分のアカウント名>/shen-lab` を入力して 下のボタンを押す。

git がわからない場合は [ここ](https://qiita.com/t-kubo0325/items/5a2b15cef0aaa92c9713) を読んでみてね。
