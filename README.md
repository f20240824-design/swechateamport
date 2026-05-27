# OSinterns — swechateamport (GitHub Pages)

Static build of the OSinterns team portfolio, ready to deploy to
https://osinterns.github.io/swechateamport/

## Deploy
1. Create a new repo named `swechateamport` under the `osinterns` GitHub org.
2. Copy the contents of this folder into the repo root and push to `main`.
3. In repo Settings → Pages, set Source to "GitHub Actions".
4. The included workflow (`.github/workflows/deploy.yml`) will publish on push.

The `.nojekyll` file disables Jekyll. `404.html` mirrors `index.html` so deep
links work as an SPA fallback.
