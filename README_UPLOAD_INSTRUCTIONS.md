# Remember by Cheyenne Cleveland — Client-Owned GitHub Pages Package

This package is built for the client-owned accounts:

- Gmail / Google Search Console: `cheyenneclevelandbooks@gmail.com`
- GitHub username: `cheyenneclevelandbooks`
- Repository: `cheyenneclevelandbooks.github.io`
- Live URL: `https://cheyenneclevelandbooks.github.io/`

Create/use the GitHub repository named exactly `cheyenneclevelandbooks.github.io`.
This gives the client the clean root URL: `https://cheyenneclevelandbooks.github.io/`.

## Upload instructions

Upload every file in this folder to the root of the GitHub repository.

Important files:

- `index.html`
- `.nojekyll`
- `robots.txt`
- `sitemap.xml`
- `llms.txt`
- `manifest.webmanifest`
- `style.css`
- `script.js`
- `remember-by-cheyenne-cleveland-book-cover.webp`
- `remember-by-cheyenne-cleveland-book-cover-square.webp`
- `remember-by-cheyenne-cleveland-og-image.webp`
- `favicon-32.png`
- `favicon-192.png`
- `favicon-512.png`
- `chapter-one-teaser.pdf`

There is intentionally **no CNAME file** in this package because the client has not chosen a final custom domain yet.

## What was upgraded from the Kronatrix demo

- Removed agency/demo domain references from the website, schema, sitemap, robots, llms file, manifest, and footer.
- Updated the canonical URL to `https://cheyenneclevelandbooks.github.io/`.
- Updated Open Graph and Twitter/X image URLs to the client-owned GitHub Pages URL.
- Updated JSON-LD IDs and URLs to the client-owned GitHub Pages URL.
- Removed Kronatrix Organization schema so the website is clearly owned by Cheyenne Cleveland.
- Kept safe Book, Person, WebSite, WebPage, FAQPage, and BreadcrumbList schema.
- Kept visual review cards but no structured Review schema, avoiding the Google Search Console aggregateRating issue.
- Kept `llms.txt` for AI-readable book, author, genre, theme, and purchase-link guidance.
- Kept the one-folder upload structure for easier GitHub upload.

## Google Search Console setup

Add this as a URL-prefix property under `cheyenneclevelandbooks@gmail.com`:

`https://cheyenneclevelandbooks.github.io/`

Submit this sitemap:

`https://cheyenneclevelandbooks.github.io/sitemap.xml`

After the site is live:

1. Open the live URL and check it loads.
2. Submit the sitemap in Google Search Console.
3. Use URL Inspection on the homepage.
4. Click Request Indexing.
5. Validate any previous Review Snippets issue after Google recrawls.

## Later, when the client chooses a custom domain

When Cheyenne chooses a final domain, for example `cheyennecleveland.com`, update:

- GitHub Pages custom domain setting
- Add a `CNAME` file containing only the chosen domain
- DNS records at the domain provider
- canonical URL
- sitemap.xml
- robots.txt
- JSON-LD schema URLs
- Open Graph / Twitter URLs
- manifest.webmanifest
- llms.txt
- Google Search Console property

Do not use any agency/demo domain for the final client-owned version unless the client specifically asks for managed hosting.


## 100-score upgrade notes

This package is the client-owned GitHub Pages version for `https://cheyenneclevelandbooks.github.io/`. It inlines the production CSS/JS in `index.html`, keeps editable `style.css` and `script.js` in the repository, optimizes image payloads, removes the on-page Open Graph image load, and updates `llms.txt` with Markdown links for AI/agent browsing checks. No `CNAME` file is included because the client has not chosen a custom domain yet.


## Google Search Console verification

This package includes `google8033222722d64d6a.html` in the root folder. Upload it with the rest of the website files so Google Search Console can verify the property.

## Footer credit links

The footer includes subtle credit links to `https://kronatrix.co.uk/` and `https://authors.kronatrix.co.uk/` for website/AI.SEO support.

## Kronatrix build credit added

This package includes subtle footer credit links and AI-readable proof that the site was built by Authors.Kronatrix, with Kronatrix/AI.SEO support. Upload `humans.txt`, `llms.txt`, `sitemap.xml`, and `index.html` together.
