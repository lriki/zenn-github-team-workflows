---
title: "コンフリクトを解決する(Webエディタ)"
---

このページでは、GitHub の Web エディタを使ったコンフリクト (他の開発者との変更箇所の衝突) の解決手順について説明します。

ドキュメントやコメントの小規模な変更は Web エディタを使うと簡単に修正できます。

::: message
ソースコードに修正が必要な場合は [コンフリクトを解決する(SourceTree)](developer-fix-conflict) で作業し、簡単に動作確認することをお勧めします。
:::

## 事前準備

\-

## 作業手順

プルリクエストで、マージボタンが無効となっており代わりに [Resolve conflicts] というボタンが現れていることを確認してください。

### Webエディタを開く

![](/images/github-team-workflows/developer-fix-conflict-web-1.png)

[Resolve conflicts] をクリックすると、 GitHub の Web エディタが表示されます。

### コードを修正する

コンフリクト個所は次のようにハイライトされています。

![](/images/github-team-workflows/developer-fix-conflict-web-2.png)

```
<<<<<<<
別の開発者の変更内容
=======
自分の変更内容
>>>>>>>
```

`<<<<<<<` ～ `>>>>>>>` の範囲内を編集し、正しいコードに直します。

![](/images/github-team-workflows/developer-fix-conflict-web-3.png)

この例では、他の開発者の変更と自分の変更を両方取り込むことにしました。

### コードを修正済みとしてマークする

編集が終わったファイルは右上の [Mark as resolved] ボタンをクリックし、修正済みとします。

![](/images/github-team-workflows/developer-fix-conflict-web-4.png)

### 修正をコミットする

全ての修正が終わると、 右上に [Commit merge] ボタンが表示されるのでクリックします。

![](/images/github-team-workflows/developer-fix-conflict-web-5.png)


## 作業後確認

プルリクエストを確認し、マージ可能になっていることを確認してください。

![](/images/github-team-workflows/developer-fix-conflict-web-6.png)

また [Commits] タブからは、Web エディタで修正した分のコミットが追加されていることを確認できます。

![](/images/github-team-workflows/developer-fix-conflict-web-7.png)



