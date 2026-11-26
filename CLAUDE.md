# Morgan Lee author website

- **Live site:** https://morgan-lee.org (the only public address). Use it to check that merged changes are live.
- **Hosting:** Cloudflare Workers, static assets only (see `wrangler.jsonc`). Merging into `main` publishes the site.
- **Retired:** `dezboi.github.io/morgan-lee` (GitHub Pages) was removed on purpose so search engines point only to morgan-lee.org. Don't reference or re-enable it.
- **Workflow:** make changes on a branch and push it. The owner opens and merges pull requests themselves unless they ask otherwise.
- All page content is in `index.html`. Styles are in `css/style.css`.
