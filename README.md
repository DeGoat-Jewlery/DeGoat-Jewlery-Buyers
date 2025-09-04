# DeGoat Jewelry – Static Site

This repository contains the single-page site for **DeGoat Jewelry** with an embedded TradingView chart, inline transparent logo, and optimized metadata.

## Quick Deploy (GitHub Pages)

1. **Create a new repo** on GitHub (public): `degoat-jewelry` (or any name).
2. **Upload** the HTML file in this repo as `index.html`.
3. On GitHub, go to **Settings → Pages**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`) / root (`/`)
   - Save. Wait ~1–2 minutes for the site to go live.
4. Your site will be available at:  
   `https://<your-username>.github.io/<repo-name>/`

## Files

- `index.html` — the entire website as a single, self-contained static page (images embedded as data URIs).

## Notes

- The header includes a **call** link (`tel:904-343-3102`) and a **text** link (`sms:904-343-3102`).
- The main hero image and logo are embedded directly in the HTML, avoiding external asset issues.
- Open Graph/Twitter/JSON‑LD metadata is included for SEO and rich previews.
- No build step is required — drag & drop into GitHub and enable Pages.

## Customizing

- To change the phone number, search for `904-343-3102` inside `index.html` and update both `tel:` and `sms:` links.
- To swap images later, replace the `data:image/...` URIs with new ones or host actual image files and update the `src` attributes.

---

© DeGoat Jewelry
