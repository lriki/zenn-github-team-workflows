---
title: "GitHub のユーザー設定を行う"
---

## 事前準備

[SSH キーを準備する](./setup-dev-ssh)

## 作業手順

### SSH 公開鍵ファイルを登録する

任意のページで右上隅にあるユーザーの画像をクリックし、[Settings] をクリックします。
![](/images/github-team-workflows/setup-dev-github-1.png)

サイドバーの [アクセス] セクションで、 [ SSH キーと GPG キー] をクリックします。
![](/images/github-team-workflows/setup-dev-github-2.png)

[New SSH key](新しい SSH キー) または [Add SSH key](SSH キーの追加) をクリックします。
![](/images/github-team-workflows/setup-dev-github-3.png)

キーの追加フォームが表示されます。

![](/images/github-team-workflows/setup-dev-github-4.png)

- [Title]
    - 自分にとってわかりやすいキーの名前を指定します。複数のキーを登録している場合その区別に利用できますが、はじめて登録する場合は好きな名前でかまいません。 `personal use` (個人使用) などとしておきましょう。
- [Key type]
    - `Authentication Key` とします。
- [Key]
    - 前章で作成した公開鍵ファイル (.pub) をテキストエディタなどで開き、内容をここへコピーします。

最後に [Add SSH key] をクリックします。

## 作業後確認

[SSH キーと GPG キー] のページから、キーが追加されていることを確認してください。

![](/images/github-team-workflows/setup-dev-github-5.png)

