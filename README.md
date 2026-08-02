# muzhi-liu.github.io

Personal academic website of Muzhi Liu, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll template and deployed via GitHub Pages.

Live site: https://muzhi-liu.github.io

## Structure

- `_pages/about.md` — home page (bio + headshot)
- `_pages/publications.md` — research page (`/research/`), rendered from `_bibliography/papers.bib`
- `_pages/cv.md` — CV page embedding `assets/pdf/Muzhi_Liu_CV.pdf`
- `_pages/watch-design.md` — watch design concepts (`/watch-design/`)
- `_data/socials.yml` — email / GitHub / CV icons
- `_config.yml` — site configuration

## Updating

- **Add a paper**: add an entry to `_bibliography/papers.bib` with a `keywords`
  field matching one of the research page sections (`cross-border`,
  `identity-voting`, `campaigns-everyday`), then push.
- **Update CV**: edit `cv/main.tex` (LaTeX source), compile with
  `pdflatex main.tex`, copy the output over `assets/pdf/Muzhi_Liu_CV.pdf`,
  then push. (Or just replace the PDF directly.)

Pushes to `main` trigger the deploy workflow, which builds the site and
publishes it to the `gh-pages` branch.

## Local preview

```bash
docker compose pull
docker compose up
# open http://localhost:8080
```
