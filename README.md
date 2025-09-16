# meYQY.github.io

A classic, static personal site for GitHub Pages (user site repo).

## Structure

- `index.html` — Home (highlights + recent writing)
- `about.html` — Brief bio, now, interests
- `work.html` — Selected work with short bullets
- `writing/` — Post index and sample posts
- `assets/style.css` — Classic, typography-first styles (light/dark)
- `404.html`, `robots.txt`, `sitemap.xml` — Basics

## Local preview

Open `index.html` directly in a browser, or run a simple static server:

```bash
python3 -m http.server 3000
# then open http://localhost:3000
```

## Publish

This is a user site repo (`<username>.github.io`). Push to the default branch (`main`/`master`) and GitHub Pages serves from the repo root.

If you have a custom domain, add a root `CNAME` file with your domain.
