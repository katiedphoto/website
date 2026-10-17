# Katie Dew Photography — dark portfolio

An original static website inspired by the spacious photographic presentation of Blacksilver. No WordPress, subscriptions, or build tools required. This package does not contain Blacksilver theme code or its demo photographs.

## Open it

Unzip the folder and double-click `index.html`. The pages, gallery filters, and lightbox work locally. Clipboard copying may require HTTPS (such as GitHub Pages).

## Before publishing

1. Open `settings.js` in Notepad. Add your email, full Instagram profile URL, and three full YouTube URLs between the quotation marks. Save.
2. The About page contact form prepares a draft in the visitor's email app. It does not send or store messages. Until an email is supplied, only Copy message is shown. If you prefer a direct web form later, use a form provider and supply its endpoint.
3. Replace the six sample JPEGs in `assets/` with your own images using the same filenames, or change the paths in the HTML. Replace the About portrait (currently `assets/mountain.jpg`) with your photo. Sample images repeat to illustrate a fuller masonry layout.
4. Edit the image titles, alt text, `data-caption`, and `data-tag` in `gallery.html`. Gallery tags are `astro`, `landscapes`, and `aerial`. Copy a complete `.shot` button to add a photo. `--ratio` controls its display crop (e.g. `3/4` portrait, `16/9` panorama); lightbox shows the full image.
5. Review the bio in `about.html`. Edit or replace the sample posts in `posts/`. Mount Maroon is a draft based on the supplied trip details; the other posts are clearly marked writing starters. Add blog cards in `blog.html` as you add articles.
6. Set `demo: false` in `settings.js` only after replacing sample photographs and drafts. Update sample labels in image descriptions and article/card metadata too.

## Upload to GitHub Pages — basic steps

If you want to keep an existing site, download a backup or use a NEW repository first.

1. Sign in to GitHub and open your chosen repository.
2. Select **Add file → Upload files**.
3. Open this extracted folder on your computer. Drag its CONTENTS (not the ZIP or outer folder) into GitHub. Include `assets`, `posts`, and the HTML/CSS/JS files. `index.html` must sit at the repository root.
4. Select **Commit changes**.
5. Go to **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**, then **main** and **/(root)**. Save.
7. Wait for GitHub to provide the site address. If your repository already uses a custom domain, preserve its existing `CNAME` file; this package intentionally does not change DNS or include a CNAME.

## Pages

- `index.html`: large photographic homepage and three collection links.
- `about.html`: spacious introduction and story, contact at the bottom. No Contact item in the top menu.
- `gallery.html`: tag-filterable masonry photographs, scrollable categories, YouTube links, keyboard/swipe lightbox.
- `blog.html`: three columns on desktop, one on phones; individual article pages included.

## Sample image sources

Six demonstration photographs downloaded from Unsplash image URLs. These are not Katie's photographs. See `assets/SOURCES.txt`. Replace with your own before launching. Google Fonts are optional; local system fonts are used if unavailable.

## Validation

HTML links and assets, tag-filter counts, JavaScript syntax, navigation, and responsive breakpoint rules checked. Browser visual QA was not available in this environment. Review on your phone before launching.
