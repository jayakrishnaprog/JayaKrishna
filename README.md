# Jaya's Website

This repository contains a simple static personal page (`index.html`) intended for publishing via GitHub Pages.

What's included
- `index.html` — the main page with header navigation, About section, interests, and a resume button.
- `.github/workflows/gh-pages.yml` — a GitHub Actions workflow that uploads the repository contents to GitHub Pages on push to `main`.

Quick deploy instructions

1. Rename the repository to `username.github.io` (replace `username` with your GitHub username) if you want a user site. Push the repository to GitHub — the site will be available at `https://username.github.io/`.

2. For a project site (not `username.github.io`):
   - Make sure the default branch is `main` (or adjust the workflow triggers).
   - The included GitHub Actions workflow will deploy the repository root to GitHub Pages automatically on each push to `main`.
   - After the first successful run, enable Pages if needed in the repository Settings → Pages (the workflow uses the Pages API and sets deployment automatically).

3. Replace placeholders in `index.html`:
   - Update the LinkedIn and GitHub hrefs to your actual profiles.
   - Update the `mailto:` link to your real email address.
   - Replace `resume.pdf` in the repo root with your actual resume file or change the button href to an external URL.

Optional improvements
- Add an `og-image.png` image at the repo root (or update the `og:image` meta tag) for a nicer social preview.
- Add a custom domain via GitHub Pages settings if you own one.

If you'd like, I can also: add a favicon, generate a simple `og-image.png`, or update links to your real profiles.
