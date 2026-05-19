# Saltwater Sanctuary — Gulf Shores Beach Guide

A Jekyll site using the **Minima** theme with a sticky sidebar navigation, hosted via GitHub Pages.

## File Structure

```
├── _config.yml          # Jekyll site configuration
├── _layouts/
│   └── default.html     # Custom layout with sidebar nav
├── _includes/
│   └── head.html        # Custom head to load sidebar CSS
├── assets/
│   └── css/
│       └── sidebar.css  # Sidebar layout & table styles
├── index.md             # Main guide content
├── Gemfile              # Ruby dependencies for GitHub Pages
└── README.md
```

## How the Sidebar Works

The `default.html` layout scans all `<h3>` headings on the page and auto-builds a sticky sidebar Table of Contents with smooth-scroll links and scroll-aware active highlighting.

## Deploying to GitHub Pages

1. Push all files to your GitHub repository.
2. Go to **Settings → Pages** and set the source to your main branch (root).
3. GitHub will build and deploy automatically.

> **Note:** The `minima` theme is built into GitHub Pages — no additional theme installation is needed.
