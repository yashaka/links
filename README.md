# links.yashaka.wtf

The source of [links.yashaka.wtf](https://links.yashaka.wtf) — one static
`public/index.html`, no build. Deployed to Cloudflare Pages by direct upload (the
project `yashaka-links`):

```sh
npx wrangler@latest pages deploy public --project-name yashaka-links --branch main --commit-dirty=true
```
