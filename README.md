# Kittuni

Public website for [Kittuni](https://kittuni.com), a private on-device iPhone expense tracker. It exists so the Google OAuth consent screen can point at a homepage and privacy policy on the verified domain.

## Pages

- `/` — homepage (`index.html`)
- `/privacy` — privacy policy (`privacy/index.html`)
- `/privacy.html` — the same privacy policy
- `/support` — support page (`support/index.html`)
- `/support.html` — the same support page

Plain static HTML and CSS. Product images in `assets/screens/` are sample screens, stored as local WebP. No JavaScript, analytics, external fonts, or build step.

## GitHub Pages

Pages deploys from the `main` branch, folder `/` (root), to the custom domain `kittuni.com`.

- The `CNAME` file contains `kittuni.com`.
- `.nojekyll` is present so Pages serves these files as-is and does not run Jekyll.

In the repository settings, GitHub Pages should be set to **Deploy from a branch**, branch **main**, folder **/ (root)**. DNS for `kittuni.com` points at GitHub Pages.
