# handbook

Gitの運用ルールについてまとめています。

## 開発フロー

本リポジトリでは **GitHub Flow** を採用しています。

開発は `main` ブランチを常にデプロイ可能な状態に保ち、機能開発やバグ修正は専用ブランチで行います。開発完了後は Pull Request を作成し、レビューおよびCIの成功を確認してから `main` ブランチへマージします。

# 開発ルール

## ブランチ

### main

* リリース用
* 常にデプロイ可能な状態を維持する
* 直接Push禁止

### feature/*

* 機能開発

### fix/*

* バグ修正

## Pull Request

* `feature/*` または `fix/*` ブランチから `main` へPull Requestを作成する
* 1人以上レビュー
* CI成功後にMerge

## Commit Message

```text
feat: ログイン画面追加

fix: NullPointerException修正

docs: README更新
```
