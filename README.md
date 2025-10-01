# My MkDocs + GitHub Pages Template

## Quick start

1. Create a new **public** repo on GitHub (e.g., `my-website`).  
2. Download and unzip this template, then push all files to your repo root.
3. Go to **Settings → Pages** and set:
   - Build and deployment: **GitHub Actions**
4. Push to `main` — the site will deploy to the `gh-pages` branch automatically.
5. Your site will be live at:  
   `https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME`

## Local preview

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

## Customize
- Edit `mkdocs.yml` (site_name, nav, theme, repo_url).
- Put content in `docs/` — use folders for structure.
- Add a custom domain in **Settings → Pages → Custom domain**.