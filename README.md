# my-works
## 公開（Cloudflare Workers）

- 公開するファイルは `public/` に置きます（現在は `public/index.html` のみ）。
- 設定は `wrangler.jsonc`。Worker 名は `my-works`、`public/` の中身だけを静的配信します。
- `main` に push すると Cloudflare Workers Builds が `npx wrangler deploy` で自動デプロイします。
