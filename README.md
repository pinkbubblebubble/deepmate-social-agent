# Social Agent Quiz — GitHub Pages

Static GitHub Pages version of the Social Agent quiz.

## Data
Writes directly to the existing Supabase project using the public publishable key.

Tables:
- `sessions`
- `answers`
- `completions`

RLS is enabled. Anonymous visitors can INSERT, but do not have SELECT/UPDATE/DELETE access.

## Deploy on GitHub Pages
1. Put `index.html` and `.nojekyll` in the repository root.
2. GitHub → Settings → Pages.
3. Source: `Deploy from a branch`.
4. Branch: `main`, folder: `/ (root)`.
5. Save.

If the repository is named `deepmate-social-agent`, the URL will normally be:
`https://<github-username>.github.io/deepmate-social-agent/`

Channel tracking still works:
- `?source=xhs`
- `?source=wechat`
- `?source=wechat_group`
