# GitHubリポジトリ作成手順

この教材を新しいGitHubリポジトリ `marketing` として使うための手順です。

## 推奨リポジトリ名

```text
marketing
```

先頭や末尾にスペースを入れないでください。GitHub上ではリポジトリ名に余計な空白を含めると、URLやコマンドの扱いで混乱します。

## 作成手順

1. GitHubで新規リポジトリを作成する
2. Repository name に `marketing` と入力する
3. Description に以下を入力する

   ```text
   Cursor社内講義向けのタスク分類・プロジェクト分類・エージェント依頼テンプレート
   ```

4. Public / Private は社内ルールに従って選択する
5. READMEやIssueテンプレートを含むこのディレクトリの内容をリポジトリへ配置する
6. GitHub Issuesを有効化する
7. 必要に応じて以下のラベルを作成する

## 推奨ラベル

| ラベル | 用途 |
| --- | --- |
| `agent-task` | エージェントへ依頼する単発タスク |
| `project` | 複数成果物や関係者を含むプロジェクト |
| `documentation` | ドキュメント作成・更新 |
| `lecture` | 社内講義資料 |
| `marketing` | マーケティング関連タスク |
| `needs-review` | 人間の確認が必要な成果物 |

## 初回運用の流れ

1. `docs/lecture-outline.md` を講義の流れとして確認する
2. `docs/task-categories.md` で依頼タスクを分類する
3. `docs/project-catalog.md` でプロジェクト化する対象を選ぶ
4. `docs/sample-agent-tasks.md` から講義デモ用の依頼を選ぶ
5. Issueテンプレートを使って実際にIssueを作る
6. CursorエージェントへIssue内容を渡す
7. Pull Requestで成果物をレビューする

## 注意事項

- 機密情報や顧客情報を講義デモに使わない
- エージェントの出力は必ず人間が確認する
- 依頼文、成果物、レビュー観点をセットで管理する
- 講義後に実務で使えた依頼例を追加していく

戦場で地図を持たずに動く奴は長く生き残れない。GitHubでも同じだ。置き場所、任務、確認方法を先に決めるんだ。
