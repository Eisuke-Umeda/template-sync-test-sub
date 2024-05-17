---
name: Add Feature
about: 機能追加についてのissue template
title: ''
labels: ''
assignees: ''

---
<!-- テスト -->
## Why
<!-- なぜこの課題に取り組むのかを記載する -->

<!-- 課題への依頼や、課題に取り組むきっかけになったSlackのスレッドのリンクを残す -->
[経緯Slack]()

## What
<!-- 具体的な仕様について記載する -->

## Acceptance Criteria
### Dev environment
<!-- 確認内容に応じて変更する -->
- [ ] Dagsterのdbtジョブが正常終了
- [ ] 各テーブルやビューの値に問題ないかサンプリングチェック

### Review
<!-- 確認内容に応じて変更する -->
- [ ] code review

### Prod  environment
<!-- 確認内容に応じて変更する -->
- [ ] master merge
- [ ] Deploy 確認 (Github Actions, Dagster手動
- [ ] Dagsterのdbtジョブが正常終了
- [ ] 各テーブルやビューの値に問題ないかサンプリングチェック
