---
title: "SourceTree をインストールする"
---

## 事前確認

[SSH キーを準備する](./setup-dev-ssh)

## 作業手順

インストーラは以下のページの [Download] ボタンからダウンロードします。

https://www.sourcetreeapp.com/

### ライセンスの確認

[スキップ] を選択します。

![](/images/github-team-workflows/setup-dev-sourcetree-1.png)

### Git のユーザー設定

ユーザー名とメールアドレスを入力します。この情報は Git のコミットに追加されるコミット者情報となります。

![](/images/github-team-workflows/setup-dev-sourcetree-2.png)

SSH キーの読み込みについてのウィンドウが表示された場合は [いいえ] としてください。



インストールが終わると、SourceTree のメイン画面が表示されます。

![](/images/github-team-workflows/setup-dev-sourcetree-3.png)



### SSH キーの登録

SourceTree メニューの [ツール] > [オプション] > [全般] > [SSH クライアントの設定] に SSH キーファイルを指定します。（ドロップダウンで "OpenSSH" を選択すると自動入力されます）

![](/images/github-team-workflows/setup-dev-sourcetree-4.png)


[OK] をクリックしてウィンドウを閉じた後は、SourceTree を再起動してください。(設定直後は Clone できないことがあるようです)


## 作業後確認


