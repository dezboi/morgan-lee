# Morgan Lee: Author Website

A simple, mobile-friendly author website built with plain HTML and CSS. It needs no build tools and no JavaScript.

## Files

```
index.html        ← all page content (edit text here)
css/style.css     ← all styling (colors are at the top)
images/           ← book covers and author photo
```

## How to update

**Text:** open `index.html` in any text editor and replace the placeholder text. Each section is labeled with a comment like `<!-- ============ ABOUT / BIO ============ -->`.

**Book covers and photo:** put your images in `images/`. Then either:
- name them the same as the placeholders (`book-1.jpg` etc.) and update the `src="images/book-1.svg"` line to the new file extension, or
- change the `src` to whatever filename you used.

Covers look best at a **2:3 ratio** (for example 800×1200 px). The author photo looks best square.

**Add a book:** in `index.html`, copy an entire `<article class="book-card"> … </article>` block, paste it after the last one, and edit it. The grid rearranges itself automatically. Upcoming books work the same way with `<article class="upcoming-card">`.

**Links:** replace each `href="#"` with your real link (store page, newsletter signup, social profile). Replace `hello@example.com` with your contact email.

**Colors:** edit the variables at the top of `css/style.css` (`--violet-600`, `--blue-600`, etc.).

## Preview locally

Double-click `index.html` to open it in your browser. After each edit, save the file and refresh the browser.

## Live site

The live website is **https://morgan-lee.org**. It is hosted on Cloudflare Workers as static files (settings in `wrangler.jsonc`).

Each time a change is merged into `main`, Cloudflare rebuilds and publishes the site, usually within a minute or two. Pull requests also get a Cloudflare preview build.

The old GitHub Pages address (`dezboi.github.io/morgan-lee`) has been retired so search engines only point to morgan-lee.org. Don't turn GitHub Pages back on.
