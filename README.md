# Minimal Hugo Poetry Site

This is a tiny, minimalist Hugo site for uploading and publishing poems.

Preview locally:

```bash
# install Hugo (https://gohugo.io/getting-started/installing/)
hugo server -D
```

Build for production:

```bash
hugo
# public/ will contain the generated site
```

Drop poem files into `content/poems/` as Markdown with front matter.

Deploy via GitHub Pages
-----------------------

1. Push this repository to GitHub (e.g., `origin` remote).
2. The workflow runs on pushes to `main` or `master` and publishes the generated `public/` site to the `gh-pages` branch.
3. In the repository settings -> Pages, set the site source to the `gh-pages` branch (if not automatic).

If you'd like I can add a small GitHub Actions badge or change the workflow behavior — tell me which branch you push from.
