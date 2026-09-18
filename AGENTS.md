# UBVL Website Agent Contract

Project code: `UBVL`
Site: Utopia Beach Villas
Repo: `gpal1973/utopia-beach-villas`
Production branch: `main`
GitHub Pages source: `main` / `(root)`
Custom domain in repo: `utopiabeachvilla.com`

## Canonical context
- Utopia Beach Villas Area: https://app.notion.com/p/1d10f76b2a3380f7b862f6b13e4486ae
- UTML GitHub Website Delivery Reference: https://app.notion.com/p/3df0f76b2a3381379b40cd74b2552086
- Validated GitHub Pages launch pattern: https://app.notion.com/p/3de0f76b2a33810da04be632a63b714c
- Source assets / editable masters: https://drive.google.com/open?id=1FVRhMbDVrw5RcTW2PiZ17g1KuUl6cXoJ&usp=drive_fs

For brand, pricing, booking, business or publish facts, resolve the current canonical Resource from the Area before editing. Do not infer durable business rules from repository content.

## Workflow
1. Read the linked Notion canon before changing brand, business, approval or publish facts.
2. Inspect the current branch, latest `main`, open PRs and deployment source before edits.
3. Use a short-lived prefixed branch and PR for material design, content, code or infrastructure changes.
4. Treat merge to `main` as a production action; merge only after explicit Georgios approval when it triggers deployment.
5. Treat `CNAME`, custom-domain and DNS changes as a separate explicit approval gate.
6. Source masters stay in Drive/Canva; repository assets are optimized runtime derivatives only.
7. Keep stable canonical asset filenames; replace in place instead of adding `final`, `v2` or duplicate production files.
8. Git commits and PRs are implementation history. Do not add `HANDOFF`, `STATE`, session-log or chat-history files.

## Current implementation boundary
- The accepted site is a lightweight static GitHub Pages implementation.
- Existing Wix-hosted media references are runtime implementation details, not source-of-truth asset storage.
- Do not change hosting stack, Pages source, custom domain or DNS as part of ordinary content/design work.
