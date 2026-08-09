# Novel Project Rules

## Source of Truth

正式な作品設定は以下を唯一の正とする。

- `00_project/`
- `01_world/`
- `02_characters/`
- `03_plot/`
- `04_manuscript/`
- `05_management/foreshadowing.md`
- `05_management/progress.md`

会話履歴、相談メモ、`05_management/ideas.md`、`05_management/unresolved.md` は正式設定として扱わない。

## Required Checks Before Writing

Codexは本文作成または改稿の前に、作業範囲に応じて以下を確認する。

- `00_project/rules.md`
- `00_project/terminology.md`
- 関係するキャラクター設定
- 関係する世界観・舞台・時系列設定
- 過去の関連エピソード
- 現在の全体・章・各話プロット
- `05_management/foreshadowing.md`
- `05_management/unresolved.md`

## Writing Rules

- キャラクター設定を守る。
- 過去話との矛盾を作らない。
- 時系列を確認する。
- 不明な設定を勝手に確定しない。
- プロットと本文は分離して管理する。
- `ideas.md`の内容は、明示的に正式ファイルへ移されるまで未確定として扱う。
- 未確定情報を本文に使う場合は、事前に確認または提案する。

## Prohibited Changes Without Proposal

Codexは勝手に以下を変更してはならない。

- キャラクターの基本設定
- 世界観の基本ルール
- 過去に確定した出来事
- 人物関係
- 年齢
- 時系列

変更が必要な場合は、先に以下を提示する。

- 変更提案
- 理由
- 影響する設定ファイル
- 影響するエピソード

## After Writing

本文作成後、Codexは以下を確認する。

- 設定矛盾
- 時系列
- キャラクター口調
- 伏線
- 管理ファイル更新の必要性

必要があれば、`05_management/foreshadowing.md`、`05_management/unresolved.md`、`05_management/progress.md`を更新する。

## Git Workflow

- 基本ブランチは`main`。
- 確定版のみ`main`へ反映する。
- 作業時は`draft/episode-XX`、`rewrite/episode-XX`、`experiment/name`などのブランチを使う。
- コミットメッセージは作品上の変更内容が分かる日本語を基本とする。

