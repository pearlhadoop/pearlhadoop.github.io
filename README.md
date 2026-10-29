# pearlhadoop.github.io

Personal engineering blog built with [Hugo](https://gohugo.io), deployed to GitHub Pages via GitHub Actions.

## Write a post

```sh
hugo new content posts/my-post.md   # creates a draft
hugo server -D                      # preview at http://localhost:1313 (includes drafts)
```

Set `draft: false` (or delete the line) when it's ready, then commit and push to `main`.

## Deploy

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds and publishes the site.
One-time setup: repo **Settings → Pages → Source: GitHub Actions**.
