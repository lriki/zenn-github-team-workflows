---
title: "Git をインストールする"
---

## 事前準備

\-

## 作業手順

### (Windows) インストーラをダウンロードして実行する

次のページからインストーラをダウンロードし、インストールしてください。

https://gitforwindows.org/

設定はすべてデフォルトのままでかまいません。

### (Windows) Git の設定を変更する

ターミナルから Git の初期設定を行います。

ターミナルの起動はスタートボタン(Windowsのロゴボタン) を右クリック > [ターミナル] (または [Windows Powershell]) が簡単です。

次のコマンドを実行してください。

```
git config --global core.autocrlf false
```

:::message
この設定は Git によりテキストファイルの改行コードが勝手に変更されないようにするための設定です。
:::

### (macOS) 

`TODO`

## 作業後確認

ターミナルから次のコマンドを実行して結果を核にしてください。

- `git --version` でバージョンが表示されること。
- (Windows の場合) `git config --global core.autocrlf` で `false` と表示されること。

