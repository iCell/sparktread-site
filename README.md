# SparkTread — support and privacy pages

The two pages the App Store listing points at:

- `index.html` → Support URL, <https://icell.github.io/sparktread-site/>
- `privacy.html` → Privacy Policy URL, <https://icell.github.io/sparktread-site/privacy.html>

They are plain static HTML, English and 简体中文 on one page each, no build step.

The authored source lives with the game in `Website/` of the SparkTread
repository; this repository is the published copy, which is public so that
GitHub Pages can serve it. Edit there, copy here, push.

Served by GitHub Pages from `main` / root (`.nojekyll` keeps Jekyll out of it).
