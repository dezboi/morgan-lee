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

**Book covers and photo:** put your images in `images/`, then change the matching `src="images/..."` in `index.html` to the new filename. Resize very large images first (about 700–900 px wide is plenty) so the page loads quickly.

Lifehacker covers are 2:3 and Karkum covers are 3:4; each section's cards are set to match. The author photo is portrait (4:5).

**Add a book:** in `index.html`, copy an entire `<article class="book-card"> … </article>` block, paste it after the last one, and edit it. The grid rearranges itself automatically. Upcoming books work the same way with `<article class="upcoming-card">`.

**Links:** replace each `href="#"` with your real link (store page, newsletter signup, social profile). Replace `hello@example.com` with your contact email.

**Colors:** edit the variables at the top of `css/style.css` (`--violet-600`, `--blue-600`, etc.).

## Preview locally

Double-click `index.html` to open it in your browser. After each edit, save the file and refresh the browser.

## Publish with GitHub Pages (free)

1. Make sure the site files are on the `main` branch of `github.com/dezboi/morgan-lee`.
2. On GitHub, go to the repo's **Settings → Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**, choose **main** and **/ (root)**, then click **Save**.
4. After a minute or two the site is live at **https://dezboi.github.io/morgan-lee/**.

Each time you push changes to `main`, the live site updates automatically.

**Custom domain (optional):** if you buy a domain such as `morganleebooks.com`, enter it under Settings → Pages → Custom domain and follow GitHub's DNS instructions.
