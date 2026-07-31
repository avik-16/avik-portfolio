# Avik Portfolio (static — no build step)

Plain HTML/CSS/JS. No npm, no build, no GitHub Actions needed.

## Files

- `index.html` — page structure/layout
- `style.css` — visual design (colors, fonts, animations)
- `data.js` — ALL editable content (projects, experience, skills, awards,
  coursework, etc.) as plain arrays. Edit this to change what the site says.
- `main.js` — turns the data into HTML and handles the scroll-in animations.
  You shouldn't need to touch this unless you're changing how something looks.

## How to preview it before publishing

Just double-click `index.html` and it'll open in your browser. (Or, if you
have Python installed: `python3 -m http.server` in this folder, then visit
`http://localhost:8000`.)

## How to publish it for free (GitHub Pages)

1. Go to github.com → New repository → name it **avik-portfolio** → Create.
2. On the new repo's page, click **"uploading an existing file"** (or
   "Add file → Upload files").
3. Drag all 4 files (`index.html`, `style.css`, `data.js`, `main.js`) into
   the upload box. Commit.
4. Go to **Settings → Pages**. Under "Build and deployment", set
   **Source: Deploy from a branch**, **Branch: main**, folder **/ (root)**.
   Save.
5. Wait 1–2 minutes. Your site is live at:
   `https://<your-username>.github.io/avik-portfolio/`

No terminal, no git commands, no build step required. To update the site
later, just edit `data.js` (or any file) in the GitHub web editor (click the
pencil icon on the file) and commit — it redeploys automatically.
