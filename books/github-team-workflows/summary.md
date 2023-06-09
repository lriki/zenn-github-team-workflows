---
title: "ワークフローの概要"
---

## ロール
本書ではいくつかの役割から Git, GitHub の使い方を説明しますが、次のロールを用いてその作業を行うべきメンバーを区別します。

| ロール | 説明 |
| ---- | ---- |
| リポジトリ管理者 | GitHub のリポジトリオーナーです。 |
| 開発者 | リポジトリで管理しているソースコードを編集し、プロダクトの制作を行います。 |
| レビュアー | 開発者が変更したソースコードをレビューし、フィードバックを行います。 |

## 準備作業

[📙開発者個人の準備作業](./setup-dev-index) からの手順に従い、各ツールをセットアップしてください。

## 開発作業の全体像

| # | 開発者の作業 | レビュアーの作業 | 備考 |
| ---- | ---- | ---- | --- |
| 1 | [リポジトリをクローンする](developer-clone-repository)<br/>または<br/>[作業場所を最新状態にする](developer-clean-workspace) | | 初回はクローンします。 |
| 2 | [自分の作業ブランチを作成する](developer-create-develop-branch) | | main ブランチから。 |
| 3 | ソースコードを変更する | | 本書では扱いません。<br/>参加しているプロジェクト<br/>の方針に従ってください。 |
| 4 | [変更をアップロードする](developer-upload-changes) | | コミット・プッシュ。 |
| 5 | [変更のレビューを依頼する](developer-submit-review) | | GitHub でプルリクエスト。 |
| 6 | | [変更をレビューする](reviewer-review) | |
| 7 | [レビューの指摘の修正を行う](developer-fix-review-feedback) | | |
| 8 | | [修正の確認を行う](reviewer-check-fix) | |
| 9 | | [変更をマージする](reviewer-marge-changes) | main ブランチへ。 |
| 10 | [マージ後の後始末](developer-cleanup) | | 続いて別機能を開発する<br/>場合は 1 から繰り返す。 |

開発中は適宜、次の作業を行ってください。

- [自分の作業ブランチへ他開発者の変更を取得する](developer-get-latest)
- [コンフリクトを解決する](developer-fix-conflict)
