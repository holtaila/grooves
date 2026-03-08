# Groove Reference — GitHub Pages

This repository hosts a single-page static site at `index.html`.

## Publish to GitHub Pages

1. Initialize a git repo in this folder.
2. Add a remote pointing to your GitHub repository.
3. Push `main`.

```bash
cd /Users/holt/groove-reference-gh-pages
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin <REPO_URL>
git push -u origin main
```

GitHub Actions in this repo deploys the page automatically on every push to `main`.

In repository settings:

- Settings -> Pages -> Source: GitHub Actions

Then open your published URL at:

- `https://<USERNAME>.github.io/<REPOSITORY>/`
