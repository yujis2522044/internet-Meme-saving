# デプロイ手順

ローカルで試す

```bash
npm install
npm start
# アプリは http://localhost:3000 で見られます
```

静的ホスティングで公開する場合（推奨）
- `public/` をそのまま Netlify / Vercel / GitHub Pages でデプロイできます。

Node サーバーをそのままホスティングする場合
- Render, Heroku, Railway など Node.js をサポートするサービスに `git push` してください。

注意: `public/` 内のオーディオファイルが存在しない場合、効果音は再生されません。音声を使う場合はファイルを `public/` に追加してください。
