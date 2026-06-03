# willdg.com

Personal website for Will D — deployed on Cloudflare Pages.

## Stack

Plain HTML + CSS, no build step.

- `index.html` — single-page introduction
- `style.css` — styles
- `_headers` — Cloudflare Pages security & cache headers

## Deploy on Cloudflare Pages

1. Push this repo to GitHub.
2. In the Cloudflare dashboard, go to **Workers & Pages → Create → Pages → Connect to Git**.
3. Select the `willdg93/willdg.com` repo.
4. Build settings:
   - **Framework preset:** None
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/`
5. Save and deploy. Add the custom domain `willdg.com` under the project's **Custom domains** tab.

Local preview: open `index.html` directly, or run any static server (e.g. `python3 -m http.server 8000`).

