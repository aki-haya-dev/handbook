# handbook
Gitの運用ルールについてまとめています。

# 開発ルール

## ブランチ

main
- リリース用
- 直接Push禁止

feature/*
- 機能開発

fix/*
- バグ修正

## Pull Request

- 1人以上レビュー
- CI成功後にMerge

## Commit Message

feat: ログイン画面追加

fix: NullPointerException修正

docs: README更新
