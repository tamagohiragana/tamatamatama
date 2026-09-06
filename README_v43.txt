たまごっち文字画像作成ツール v43

v42からの主な変更
- QR生成をドット単位で描画し、補間によるぼやけを防止
- QRを300px化（誤り訂正Hは維持）
- QR読み取りを強化：BarcodeDetector → jsQR複数サイズ → 左下重点クロップ → グレースケール/複数閾値
- 旧 TAMA1: QR と現在のGitHub Pages ?text= QRの両方に対応
- 選択中スタンプに「上下反転」ボタンを追加
- 選択中スタンプに「白枠：ON/OFF」ボタンを追加
- 上下反転と白枠はPNG保存・共有にも反映
- 既存のQR最前面、背景/スタンプ自動取得、既存50音MAPは維持

配置：v42と同じくパッチ形式です。
root/index.html を上書きし、backgrounds/index.json、stickers/index.json、.github/workflows/update-asset-index.yml を配置してください。
