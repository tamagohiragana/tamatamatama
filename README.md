# たまごっち文字メーカー

ひらがなをオリジナルのたまごっち文字画像に変換し、背景・文字色・白アウトライン・透過PNGスタンプを組み合わせて画像を作成できるWebツールです。

## GitHub Pagesで公開する方法

1. GitHubで新しいPublicリポジトリを作成します。
2. このフォルダの中身をリポジトリのルートにアップロードします。
3. **Settings → Pages** を開きます。
4. **Build and deployment** の Source を **Deploy from a branch** にします。
5. Branch を `main`、Folder を `/ (root)` にして保存します。
6. 数分後に表示されたGitHub PagesのURLへアクセスします。

## ファイル構成

- `index.html` — メインページ
- `glyphs/` — たまごっち文字PNG
- `stickers/` — 標準透過PNGスタンプ8種類
- `backgrounds/` — 標準背景8種類

QRコード生成・読み取りにはブラウザからCDN経由で `qrcode-generator` と `jsQR` を読み込みます。
