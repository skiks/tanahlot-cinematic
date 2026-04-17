# tanahlot — client site (alsite)

Client site built with the alsite kit. Deployed to **https://tanahlot.sites.alen.cool**.

## File layout — strict separation

- **Root** (`index.html`, `assets/`, `vercel.json`): PUBLIC, on Vercel
- **`_source/`**: brand materials, variants, previews, source HTML — internal, client-shareable
- **`_internal/`** (if present): project notes, contacts — never shared
- **Costs / margins**: live at `/workspace/alsite/_costs/tanahlot.md` — NEVER in this dir

**Never put prices, API costs, or internal margins inside any file in this client repo.**

## Project info
- **Slug:** tanahlot
- **GitHub:** https://github.com/skiks/tanahlot-site (or similar — check `git remote -v`)
- **Vercel prod:** https://tanahlot.sites.alen.cool
- **Dev worktree (if exists):** `.wt/dev/` (branch `dev` → preview deploy)

## Scope
Stay inside `/workspace/alsite/clients/tanahlot/`. Don't edit the alsite kit itself (components, styles) — open a session at `/workspace/alsite/` for that.

## Sharing with client
- **Live site:** https://tanahlot.sites.alen.cool
- **Source bundle:** https://github.com/skiks/tanahlot-site/archive/refs/heads/main.zip (includes `_source/` with brand materials; safe because costs live elsewhere)
- **Never** zip from local disk — you might include `_internal/` or uncommitted files.

## Tooling available
alsite + apify-scrape + site-qualify + spline-3d-integration skills are visible here via `.claude/` walk-up. Global skills (karpathy-guidelines, deploy-to-coolify) also visible.
