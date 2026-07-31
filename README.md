# Anumita Alur — Portfolio Site

A 3-page static site (Home, About, Experience) built from your resume, styled with a custom
"logic model" motif since evaluation design is core to your work.

## Files
- `index.html` — home page (hero, stats, focus areas, featured roles, connect)
- `about.html` — bio, "logic model of my own" (Inputs → Activities → Outputs → Outcomes), skills/tools
- `experience.html` — full role timeline, education, publications
- `styles.css` — all styling (one shared stylesheet, no build step)
- `nav.js` — mobile menu toggle

## Publish it on GitHub Pages
1. Create a new GitHub repo named exactly `<your-username>.github.io` (or any name if you're okay with a `/repo-name/` URL).
2. Upload these files to the repo root (or push via git).
3. In the repo, go to **Settings → Pages**, set branch to `main` (or `master`) and folder to `/root`.
4. Your site will be live at `https://<your-username>.github.io` (or `.../repo-name/`) within a minute or two.

## Things you'll likely want to swap in next
- **Photo**: the header currently uses your initials as a placeholder avatar circle. Send a headshot and I'll wire it in.
- **LinkedIn URL**: I used `linkedin.com/in/anumitaalur` from your resume — double check it's correct.
- **Domain**: if you buy a custom domain later, GitHub Pages supports that too.

## Easy edits
- Text lives directly in the HTML files — search for the sentence you want to change and edit it.
- Colors and fonts are all defined as CSS variables at the top of `styles.css` under `:root`.
