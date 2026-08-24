# linshom-site

Public website, documentation and press kit for **לנשום (Linshom)** — a Hebrew
guided-breathing app for Android.

The app's source lives in a separate, private repository. This repo holds only
what is meant to be public.

## Pages

| File | Purpose |
|---|---|
| `index.html` | Landing page. The hero circle runs the app's real 4-7-8 and box timings. |
| `support.html` | Support and FAQ — the URL for Play's support field. |
| `privacy-policy.html` | Privacy policy — **required** by Google Play, must stay publicly reachable. |
| `press/` | Store graphics and listing copy. |
| `assets/site.css` | Shared design tokens: colours sampled from the app icon, Suez One + Assistant + Heebo. |

Static HTML, no build step. Open any page directly in a browser.

## GitHub Pages

Settings → Pages → **Deploy from a branch** → `main` / `/ (root)`.

Pages on a *private* repo needs a paid plan; on Free this repo must be public.
That is why it is split from the app source.

`.nojekyll` is present so Jekyll does not process the files.

## After changing anything

Open the deployed privacy-policy URL in a **private browser window**. Play
reviewers fetch it logged-out — if it 404s or asks for a login, the app
submission is rejected on that alone.
