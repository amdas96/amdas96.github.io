# Launch checklist

## What's in this folder
- `index.html` — home page, including the Contact section at the bottom
- `projects.html`, `experience.html`, `skills.html`, `certifications.html` — one real page each, linked from the nav bar
- `style.css` — shared styling for every page (edit once, all pages update)
- `resume.pdf` — add your own resume file with exactly this name

## 1. Get a GitHub account (if you don't have one)
github.com → sign up, free forever.

## 2. Create the repo
- New repository named exactly: `your-username.github.io`
- Public, no README/license needed (you already have files)

## 3. Add your files
Upload all the files above to the repo root (drag-and-drop on github.com works — no git command line needed). Keep them all in the same folder so the links between pages work.

## 4. Turn on GitHub Pages
- Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / root → Save
- Your site is live in 1–2 minutes at `https://your-username.github.io`

## 5. Personalize the content
Open each HTML file in any text editor (or GitHub's built-in editor — pencil icon on the file) and replace:
- `your-handle` (LinkedIn, GitHub) and `you@email.com` — appears on the home and contact pages
- Hero headline and pitch (`index.html`)
- The placeholder projects (`projects.html`) — swap in real, public-safe projects (personal, coursework, or open-source; leave out confidential employer work), with real links
- Experience bullets (`experience.html`)
- Skills and "currently learning" pills (`skills.html`)
- Certifications (`certifications.html`)

No build step, no npm, no database — every page is plain HTML with one shared CSS file. Editing is just editing text and refreshing the page.

## Updating later
Edit any file directly on github.com (pencil icon → edit → commit). Changes go live automatically within a minute or two. Since all six pages share `style.css`, changing a color or font there updates the whole site at once — but content changes (a new project, a new cert) need to be made on that page's own file, since the pages aren't otherwise linked.

## Custom domain (optional, still free)
GitHub Pages supports a custom domain if you buy one later (repo Settings → Pages → Custom domain). Not required — the default `github.io` URL is fine for a resume link.
