# Fish World privacy policy site

This folder is the content of a small **public** GitHub repository
that hosts the Fish World privacy notice via GitHub Pages.

It is intentionally separate from the main Fish World source repository
(which is private). The two are unrelated.

## Files

- `index.md` — the published privacy notice. Edit this file when the
  policy changes; bump the "Last updated" date inside.
- `_config.yml` — Jekyll config for GitHub Pages. Picks the Cayman
  theme so the page renders cleanly without custom CSS.

## How to publish (one-time setup)

1. On GitHub, click **New repository**.
2. Owner: your personal account. Name: `fishworld-privacy`.
   Visibility: **Public** (required for free GitHub Pages).
   Do **not** initialize with a README.
3. Locally, copy this folder's contents into a new directory and push:

   ```bash
   mkdir fishworld-privacy && cd fishworld-privacy
   # copy index.md, _config.yml, README.md into here
   git init
   git add .
   git commit -m "Initial: Fish World privacy notice"
   git branch -M main
   git remote add origin https://github.com/<your-username>/fishworld-privacy.git
   git push -u origin main
   ```

4. On GitHub, open the new repo → **Settings → Pages**.
5. Under **Source**, choose **Deploy from a branch**, branch `main`,
   folder `/ (root)`. Click **Save**.
6. Wait ~1 minute. Refresh the Pages settings page — it will show:

   > Your site is live at `https://<your-username>.github.io/fishworld-privacy/`

7. Paste that URL into Google Play Console → App content → Privacy
   policy.

## How to update later

Edit `index.md`, bump the "Last updated" date, commit, push. GitHub
Pages rebuilds in under a minute. The URL stays the same.

## Things to fill in before going live

Search `index.md` for these and confirm each:

- `roney4972@gmail.com` — **create this Gmail account first**
  and check it. Reviewers and parents will email it. If you'd rather
  use a different address, find/replace the placeholder.
- "Last updated: May 26, 2026" — update on every material change.

That's it — no other personal info or addresses appear in the policy.
