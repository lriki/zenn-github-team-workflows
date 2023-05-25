---
title: "リポジトリをクローンする"
---

## 事前準備



## 作業手順

まず、GitHub のリポジトリページを開きます。

右上のほうにある [Code] ボタンをから、 [Local] > [SSH] と選択し、 URL をコピーします。(先頭が `git@` となっている点に注意してください)

![](/images/github-team-workflows/developer-clone-repository-1.png)

続いて SourceTree を開き、メニューの [ファイル] > [新規/クローンを作成する] をクリックします。

![](/images/github-team-workflows/developer-clone-repository-2.png)

コピーした URL を張り付けます。

Tab キーを押したり、他のテキストボックスをフォーカスすると、リポジトリがクローン出来るかどうか、チェックが走ります。自動的に入力されるクローン先のフォルダパスを確認してください。

![](/images/github-team-workflows/developer-clone-repository-3.png)

::: message
クローン先のフォルダパスは日本語を含まないことが推奨されます。
:::

確認したら、 [クローン] をクリックします。

クローンに成功すると、次のような画面が表示されます。

![](/images/github-team-workflows/developer-clone-repository-4.png)

::: message
デフォルトのクローンフォルダは [ツール] > [オプション] > [全般] > [Repo settings] > [プロジェクトフォルダ] で変更できます。
:::

## 作業後確認

- [エクスプローラで開く] をクリックし、フォルダにファイルが作られていることを確認してください。

