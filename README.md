# Ram Sundar — Portfolio

A static, multi-page portfolio. No build step, no frameworks to install — just HTML, CSS and the fonts loaded from Google Fonts. Open `index.html` in a browser to preview.

## Files
- `index.html` — home page (hero, live products, work grid, about, experience, contact)
- `projects/` — one detail page per project (onexfort, getrostered, bookaremovalist, bos, planq, credence)
- `styles.css` — shared stylesheet for every page
- `resume.pdf` — the résumé the "Download résumé" buttons point to

## Things to finish
- **Planq description** — `projects/planq.html` has a highlighted placeholder box. Replace it with one line on what Planq does for its users.
- **GitHub link** — not added yet. When you have one, it can go in the nav and the contact section.
- **Screenshots (optional)** — the project pages are text-only right now. Adding a screenshot or two per project would lift them a lot.

## Put it online (all free)

### Option A — GitHub Pages (also gives you a GitHub presence)
1. Create a repo, e.g. `ram-sundar-portfolio`.
2. Upload all these files (keep the `projects/` folder as-is).
3. Repo **Settings → Pages → Build from branch → main → /(root)**.
4. Your site goes live at `https://<username>.github.io/ram-sundar-portfolio/`.

### Option B — Vercel or Netlify (easiest, drag-and-drop)
1. Sign in at vercel.com or netlify.com.
2. Drag the whole `portfolio` folder into the dashboard (Netlify) or import the repo (Vercel).
3. It deploys in seconds and gives you a URL. Add a custom domain later if you want.

## Custom domain (optional)
A domain like `ramsundar.dev` (~₹800–1500/year) makes it look sharper on a résumé and LinkedIn. Both hosts above let you attach one for free.

## Editing tips
- Colours are defined once at the top of `styles.css` under `:root`. Each project's colour comes from a `cat-*` class (e.g. `cat-teal`) on the card and page body.
- To add a project: copy any file in `projects/`, change the text, stack tags and `cat-*` colour, then add a matching card in `index.html`.
