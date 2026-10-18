# links.yashaka.wtf

The source of [links.yashaka.wtf](https://links.yashaka.wtf) — one static
`index.html`, no build. Deployed to Cloudflare Pages by direct upload (the
project `yashaka-links`):

```sh
npx wrangler@latest pages deploy . --project-name yashaka-links --branch main --commit-dirty=true
```
