# Qilong Blog

This repository is a Hugo site using the Terminal theme.

## Local development

Install Hugo Extended, then run:

```bash
hugo server --buildDrafts
```

## Add a post

```bash
hugo new content posts/my-first-post.md
```

## Deploy

Push to `main`. GitHub Actions builds the site and deploys it to GitHub Pages.
