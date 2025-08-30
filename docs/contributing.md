# Contributing to Logchange Docs

Thank you for helping improve our documentation!

## Edit a page

- Click the pencil icon in the top-right of any page to edit directly on GitHub.
- Propose changes via a Pull Request.

## Run the site locally

Prerequisites:
- Python 3.8+

Install and serve:

```bash
pip install mkdocs mkdocs-material
mkdocs serve
```

Open http://127.0.0.1:8000 in your browser. Changes reload automatically.

## Add a new tool

1. Create a new folder under `docs/tools/<tool-name>/` with at least:
   - `getting-started.md`
   - `usage.md`
   - `faq.md`
   - `reference.md`
2. Update `mkdocs.yml` to add navigation entries under `nav -> Tools`.
3. Add links from `docs/index.md` Quick Links if desired.

## Content guidelines

- Keep Getting Started concise with prerequisites, installation, and a quick start example.
- Put detailed commands and options under Reference.
- Add examples and troubleshooting notes under Usage and FAQ.

## Build and deploy

- On merge to `main`, GitHub Actions builds and deploys the site to GitHub Pages automatically.
- The site is published at: https://logchange.github.io/.github/
