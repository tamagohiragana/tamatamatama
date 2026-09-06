v42 自動取得完全修正版

【重要】このZIPは既存GitHub Pagesプロジェクトへの差し替え用です。

1. index.html → リポジトリのルートに上書き
2. backgrounds/index.json → backgrounds/ に上書き
3. stickers/index.json → stickers/ に上書き
4. .github/workflows/update-asset-index.yml → 同じパスに追加

これで今後はPNGを backgrounds/ または stickers/ に追加するだけで、GitHub Actionsがindex.jsonを自動更新します。
index.jsonを手で編集する必要はありません。

背景・スタンプ一覧は同一GitHub Pages上のindex.jsonを読むため、GitHub APIのレート制限で「自動取得に失敗」する問題も避けられます。
