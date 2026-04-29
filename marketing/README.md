# marketing

Cursor社内講義向けの教材リポジトリです。

このリポジトリは、社内でCursorとAIエージェントを使うときに「何を任せられるのか」「どう依頼すればよいのか」「どの単位でプロジェクト化するのか」を説明するための材料をまとめています。

## 目的

- Cursorの基本的な使い方を社内向けに説明する
- エージェントへ依頼しやすいタスクを分類する
- 実務プロジェクトに落とし込みやすい依頼パターンを整理する
- GitHub Issues / Pull Requests と組み合わせた運用例を示す

## 想定する受講者

- Cursorをこれから使い始める社員
- AIエージェントへ業務を依頼したい非エンジニア
- GitHub上でタスク管理やレビューを行うチーム
- 社内の業務改善・マーケティング・営業支援を進める担当者

## リポジトリ構成

```text
marketing/
├── README.md
├── docs/
│   ├── lecture-outline.md
│   ├── task-categories.md
│   ├── project-catalog.md
│   ├── agent-briefing-template.md
│   ├── sample-agent-tasks.md
│   ├── github-setup.md
│   └── cursor-account-history.md
└── .github/
    ├── pull_request_template.md
    └── ISSUE_TEMPLATE/
        ├── agent-task.yml
        └── project-request.yml
```

## 講義で扱う流れ

1. Cursorでできることを把握する
2. エージェントに任せるタスクを分類する
3. 依頼文を具体化する
4. GitHub Issueとして管理する
5. Pull Requestで成果物を確認する
6. 社内運用ルールに落とし込む

## 使い方

1. `docs/lecture-outline.md` を使って講義の流れを説明する
2. `docs/task-categories.md` で依頼できるタスクの種類を確認する
3. `docs/project-catalog.md` でプロジェクト単位の活用例を確認する
4. `docs/agent-briefing-template.md` を使って依頼文を作成する
5. `docs/sample-agent-tasks.md` で講義デモ用の依頼例を確認する
6. `docs/github-setup.md` を参考にGitHubリポジトリとして作成する
7. `.github/ISSUE_TEMPLATE/agent-task.yml` と `.github/ISSUE_TEMPLATE/project-request.yml` を使ってタスクをGitHub Issue化する
8. `.github/pull_request_template.md` を使ってPull Requestの確認観点をそろえる
9. `docs/cursor-account-history.md` に、このアカウントで関わったソフト・業務の実例を追記する（講義で実話として話す場合）

## 運用方針

- 依頼は「目的」「背景」「成果物」「制約」「確認方法」を明記する
- エージェントには小さく検証可能な単位で依頼する
- 最終成果物はPull Requestで確認する
- 人間が判断すべき内容と、エージェントに任せる作業を分ける

現実を見るんだ。AIに丸投げすれば仕事が消えるわけじゃない。だが、任せ方を覚えれば、仕事の密度は変えられる。
