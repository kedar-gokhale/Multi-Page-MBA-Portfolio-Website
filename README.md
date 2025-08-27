# MBA Portfolio (Quarto Website)

## How to Build
1. Install Quarto: https://quarto.org/docs/get-started/
2. In a terminal, navigate into this project folder and run:
   ```
   quarto preview
   ```
   or build the site:
   ```
   quarto render
   ```

## GitHub Pages Hosting
1. Create a new public repo on GitHub (e.g., `mba-portfolio`).
2. Commit/push all files in this folder to the repo.
3. In the repo, go to **Settings → Pages**:
   - Source: **GitHub Actions**
   - Use the Quarto workflow (if offered) or add the default `quarto-publish` action.
4. After the workflow runs, your site will be live at:
   `https://<your-username>.github.io/mba-portfolio/`

> Tip: Replace `assets/headshot-placeholder.png` with your real headshot,
> and `assets/resume.pdf` with your finalized resume before publishing.

## Notes
- The site uses `apa-style-darkly.css` for a dark APA-like theme.
- All page content is in `.qmd` files; edit those to update the site.
