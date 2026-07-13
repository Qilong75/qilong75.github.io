# Qilong Blog

This repository is a clean Hugo site initialized with `hugo new site`.

## Local development

Install Hugo Extended, then run:

```bash
hugo server --buildDrafts
```

## Add a theme

Install a Hugo theme under `themes/`, then set it in `hugo.toml`:

```toml
theme = "theme-name"
```

## Add a post

```bash
hugo new content posts/my-first-post.md
```

## Deploy

Push to `main`. GitHub Actions builds the site and deploys it to GitHub Pages.
