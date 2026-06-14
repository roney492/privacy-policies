# Age of Power privacy policy site

This folder is the content of a small **public** GitHub repository that hosts
the Age of Power privacy policy via GitHub Pages. Google Play Console requires
a publicly reachable privacy policy URL for the listing.

It is intentionally separate from the main (private) game repository.

## Files

- `index.md` — the published policy. Edit it when the policy changes and bump
  the "Last updated" date inside.
- `_config.yml` — Jekyll config for GitHub Pages (Cayman theme; renders
  cleanly with no custom CSS).

## How to publish (one-time)

1. On GitHub, click **New repository**.
2. Owner: your account. Name: `ageofpower-privacy`. Visibility: **Public**
   (required for free GitHub Pages). Do **not** initialize with a README.
3. Locally, copy this folder's contents into a new directory and push:

   ```bash
   mkdir ageofpower-privacy && cd ageofpower-privacy
   # copy index.md, _config.yml, README.md into here
   git init
   git add .
   git commit -m "Initial: Age of Power privacy policy"
   git branch -M main
   git remote add origin https://github.com/<your-username>/ageofpower-privacy.git
   git push -u origin main
   ```

4. On GitHub: new repo → **Settings → Pages**.
5. Under **Source**, choose **Deploy from a branch**, branch `main`, folder
   `/ (root)`. Click **Save**.
6. Wait ~1 minute, refresh — it shows:

   > Your site is live at `https://<your-username>.github.io/ageofpower-privacy/`

7. Paste that URL into Google Play Console → App content → Privacy policy.

## Updating later

Edit `index.md`, bump the "Last updated" date, commit, push. GitHub Pages
rebuilds in under a minute. The URL stays the same.

## Before going live

- Confirm **roney4972@gmail.com** is monitored — reviewers and players email it.
- Update "Last updated: June 14, 2026" on every material change.
