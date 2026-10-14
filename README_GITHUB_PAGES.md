# Tabimix legal site — GitHub Pages公開手順

公開先：`https://bokchoyworks-stack.github.io/tabimix-legal/`

1. GitHubへ `bokchoyworks-stack` でログインする。
2. 右上の「＋」→「New repository」。
3. Repository name：`tabimix-legal`。Publicを選び、README等は追加せず「Create repository」。
4. Googleドライブの「マイドライブ/Tabimix-Legal」からファイルをダウンロードする。ZIPの場合は展開する。「uploading an existing file」を押し、`index.html`・`terms.html`・`support.html`・`style.css` をまとめてドラッグする。フォルダごとではなく、4ファイルをリポジトリの直下に置く。このREADMEも必要に応じて追加できる。
5. Commit messageを `Add Tabimix legal pages` として「Commit changes」。
6. 「Settings」→「Pages」→ Source「Deploy from a branch」、Branch `main` / `/(root)` →「Save」。
7. 数分後に公開先を開き、3ページを確認する。日本語・Englishボタン、ページ間リンク、メールリンクを確認する。

構成：ExamCamp-Legalと同じ、ヘッダーの言語ボタン（各言語の本文への移動）、要点カード、番号付き見出し、フッター。日本語とEnglishを同じHTMLに収録。JavaScriptやビルド作業は不要。

対象：Tabimix（iPhone/iPad向け旅行計画アプリ）、App Store Apple ID `6822153798`、開発者 `bokchoyworks`。
制定日：2026年10月14日。連絡先：`bokchoyworks@gmail.com`。

公開設定の参考：[GitHub公式の公開元設定手順](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)。

App Store Connectに入れるURL（GitHub Pages公開後）：
- 利用規約（説明文の末尾・審査メモ）：`https://bokchoyworks-stack.github.io/tabimix-legal/terms.html`
- プライバシーポリシーURL：`https://bokchoyworks-stack.github.io/tabimix-legal/`
- サポートURL：`https://bokchoyworks-stack.github.io/tabimix-legal/support.html`
