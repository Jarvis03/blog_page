# Getting Started

## Local preview

```bash
# (optional) create and activate a virtualenv
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\activate

# install deps
pip install -r requirements.txt

# run local dev server
mkdocs serve  # visit http://127.0.0.1:8000
```

## Project layout

```
.
├── docs/
│   ├── index.md
│   └── guide/
│       └── getting-started.md
├── mkdocs.yml
└── .github/workflows/pages.yml
```

## Deploys

Every push to `main` triggers CI to build the site and publish to the `gh-pages` branch.
Enable **Settings → Pages → Source: Deploy from a branch** (or the new **GitHub Actions** mode).