# Goals Tracker website

Public landing page and privacy policy for [Goals Tracker](https://play.google.com/store/apps/details?id=com.goalstracker.app) (`com.goalstracker.app`).

The Android app itself lives in a separate private repository.

## URLs (after GitHub Pages is on)

| Page | URL |
| --- | --- |
| Landing | https://zepedrodev.github.io/goals-tracker/ |
| Privacy policy | https://zepedrodev.github.io/goals-tracker/privacy/ |

Paste the privacy URL into Play Console → App content → Privacy policy.

## Enable GitHub Pages

1. Repo **Settings → Pages**.
2. **Source:** Deploy from a branch.
3. Branch: `main`, folder: `/ (root)`.
4. Save and wait for the HTTPS site.

`.nojekyll` is in the repo so GitHub does not process the files as Jekyll.

## Local preview

Serve the repo root with any static file server so `/privacy/` resolves:

```bash
npx --yes serve .
```

Then open the printed local URL.
