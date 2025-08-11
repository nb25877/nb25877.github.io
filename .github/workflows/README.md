# MSc Cyber Security e-Portfolio (MkDocs + Material)

**Live:** https://nikunjb.com  (served from this repo via GitHub Pages)

## Quick start
1. Install Python 3.11+ and `pip`.
2. `pip install -r requirements.txt`
3. `mkdocs serve` → open http://127.0.0.1:8000
4. Edit files in `docs/`. Push to `main` to auto-deploy.

## Structure
- `docs/index.md` – **About Me** (landing)
- `docs/modules/*` – module pages (with **Learning Outcomes** + **Reflection**)
- `docs/certifications.md`
- `docs/contact.md`
- `docs/CNAME` – custom domain `nikunjb.com`

## Adding a new module
Copy `docs/modules/_template-module.md` → `docs/modules/<your-module>.md`, add to `nav` in `mkdocs.yml`.

## Tags
Add `tags:` in the YAML front matter of any page. See `docs/modules/introduction-to-computing.md`. A tag index is auto-generated at `/tags/`.

## License
Text: CC BY-NC 4.0. Code: MIT.