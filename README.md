# Akhil Mohandas: portfolio site

Plain HTML + CSS, no build step. Hosted free on GitHub Pages at https://amdas96.github.io

## Files
- `index.html`: home (hero, key results, about, tool set, featured projects, contact)
- `projects.html`: project cards (2 x 2 grid + "coming soon")
- `experience.html`: work experience and education
- `skills.html`: skills in six groups
- `certifications.html`: certifications and awards
- `project-template.html`: copy this to write a full case study for any project
- `style.css`: ALL colors, sizes and layout (edit once, every page updates)
- `assets/`: images (`profile.svg`, `placeholder.svg`, `favicon.svg`)
- `resume.pdf`: add your own file with exactly this name

## Deploy / update
1. Upload everything to the root of your `amdas96.github.io` repo, including the `assets` folder (drag the folder onto github.com). Overwrite existing files.
2. Delete the old `README.md` copy if you do not want it shown, and any leftover `contact.html`.
3. Edit later on github.com: open a file, click the pencil, edit, Commit. Live in 1-2 minutes.

## Do these 6 things before sharing the link
1. **Photo**: save a square photo as `assets/akhil.jpg`, then in `index.html` change `assets/profile.svg` to `assets/akhil.jpg`.
2. **Project screenshots**: save images in `assets/` and replace `assets/placeholder.svg` in each card in `projects.html` (and the 3 cards on the home page).
3. **Resume**: add `resume.pdf` to the repo root (the buttons 404 without it).
4. **Credential links**: if you have URLs for your certificates, paste them using the commented snippet in `certifications.html`.
5. **Check wording**: confirm "Cadd Center" spelling and add the CGPA scale in `experience.html` (comments mark both); confirm the Nielsen bullets are fine to share publicly.
6. **Add one result per project** (accuracy, % improvement) at the end of each project description.

## Common edits
- **Background / colors**: top of `style.css`, the `:root` block (`--paper`, `--ink`, `--accent`). If you change `--paper`, also change `--paper-glass` to the same color.
- **Content width**: `--max` in `style.css`.
- **Font sizes**: only three sizes are used: `--text-sm`, `--text-md`, `--text-lg`.
- **Nav links**: the nav is repeated in each HTML file, so edit it in all pages.
- **New project card**: copy one `<article class="card">` block in `projects.html`.
- **New case study page**: copy `project-template.html`, rename it, and link a card's link to it.
