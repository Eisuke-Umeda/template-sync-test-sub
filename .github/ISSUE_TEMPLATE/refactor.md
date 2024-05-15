---
name: Refactor
about: リファクタリング用のissue template
title: ''
labels: ''
assignees: ''

---

## Why
<!-- リファクタリングの目的を記載する -->

<!-- リファクタリングのきっかけや具体的な議論などのSlackのスレッドのリンクを残す -->
[経緯Slack]()

## What
<!-- 具体的な修正内容について記載する -->

## Acceptance Criteria
### Dev environment
<!-- 確認内容に応じて変更する。リグレッションテストの項目を盛り込む。 -->
- [ ] Dagsterのdbtジョブが正常終了
- [ ] 各テーブルやビューの値に問題ないかサンプリングチェック

### Review
<!-- 確認内容に応じて変更する -->
- [ ] code review

### Prod  environment
<!-- 確認内容に応じて変更する。リグレッションテストの項目を盛り込む。 -->
- [ ] master merge
- [ ] Deploy 確認 (Github Actions, Dagster手動
- [ ] Dagsterのdbtジョブが正常終了
- [ ] 各テーブルやビューの値に問題ないかサンプリングチェック
