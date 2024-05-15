---
name: Change Feature
about: 機能変更用のissue template
title: ''
labels: ''
assignees: ''

---

## Why
<!-- なぜこの課題に取り組むのかを記載する -->

<!-- 課題への依頼や、課題に取り組むきっかけになったSlackのスレッドのリンクを残す -->
[経緯Slack]()

## As Is
<!-- 現在の状態について記載する -->

## To Be
<!-- 理想的な状態について記述する -->

## Acceptance Criteria
### Dev environment
<!-- 確認内容に応じて変更する -->
- [ ] Dagsterのdbtジョブが正常終了
- [ ] 各テーブルやビューの値に問題ないかサンプリングチェック

### Review
<!-- 確認内容に応じて変更する -->
- [ ] code review
- [ ] 上記エビデンスの確認

### Prod  environment
<!-- 確認内容に応じて変更する -->
- [ ] master merge
- [ ] Deploy 確認 (Github Actions, Dagster手動
- [ ] Dagsterのdbtジョブが正常終了
- [ ] 各テーブルやビューの値に問題ないかサンプリングチェック
