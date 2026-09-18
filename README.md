# Utopia Beach Villas

Static GitHub Pages website for Utopia Beach Villa in Vourvourou, Halkidiki.

## Site structure
- `index.html` — homepage
- `villa.html` — villa details
- `gallery.html` — gallery and location content
- `styles.css` — shared responsive styling
- `assets/` — repository-owned runtime assets
- `CNAME` — production custom-domain declaration for `utopiabeachvilla.com`
- `AGENTS.md` — repository-specific AI/operator handoff contract

## Deployment
- `main` is the production branch.
- GitHub Pages uses `main` / `(root)` for this delivery pattern.
- Material changes should use a short-lived prefixed branch, preview/QA, pull request, human review and then merge.
- A merge to `main` may publish immediately and therefore requires explicit approval.
- Changing or removing `CNAME`, changing the Pages source, or changing DNS is a separate approval-gated infrastructure action.

## Asset ownership
Source assets and editable masters are maintained outside GitHub. The repository should contain only web-ready runtime derivatives required by the site. Some accepted pages currently reference Wix-hosted media; those URLs are implementation dependencies, not master-asset storage.

Do not add repository-local handoff/history/state files; use Git commits and pull requests for implementation history and the canonical UTML workspace for durable decisions and project state.
