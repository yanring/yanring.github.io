# Zijie Yan's homepage

A small, responsive personal homepage built with HTML and CSS. No build step or external dependencies.

## Preview

Open `index.html` directly in a browser, or run this command from this directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then visit http://127.0.0.1:8000.

## Edit

Update the biography and links in `index.html`. Adjust the layout and colors in `style.css`.

Replace `portrait.jpg` to use a different photo. Publication details are linked to their arXiv sources.

## Publish to GitHub Pages

The site is published at https://yanring.github.io/ from the root of the `main` branch. Push changes to `main` to deploy updates.

In **Settings → Pages**, the source is **Deploy from a branch**, with **main** and **/ (root)** selected. `.nojekyll` keeps the site as plain static files. `robots.txt` and `sitemap.xml` allow search crawlers to discover the homepage.

GitHub's setup guide: https://docs.github.com/en/pages/quickstart
