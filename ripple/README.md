# Ripple — Privacy Policy (hosting)

This folder is self-contained and ready to drop into the repo you host via
**GitHub Pages**.

## Files
- `index.html` — the page that gets served. Self-contained (inline CSS, inline
  SVG logo), no Jekyll theme or build step required. **This is what Play links to.**
- `privacy-policy.md` — the same content in Markdown, kept as the editable source.
  Edit this when the policy changes, then mirror edits into `index.html`.

## Publish on GitHub Pages
1. Create/choose a public repo (e.g. `ripple-privacy`).
2. Copy the contents of this folder into the repo root (at minimum `index.html`).
3. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a
   branch*, Branch = `main`, folder = `/ (root)`. Save.
4. After it builds, the policy is live at:
   `https://<your-user>.github.io/<repo>/`
   (or your custom domain if you add a `CNAME`).

Because `index.html` is present, Pages serves it directly — Jekyll is not needed.
(If you ever publish only the `.md`, add an empty `.nojekyll` file to skip Jekyll,
or let Jekyll render it with a theme.)

## Then in Play Console
Paste the live URL into **App content → Privacy policy**. A privacy policy URL is
required even though Ripple collects no data.
