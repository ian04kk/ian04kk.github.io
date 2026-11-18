# Agus Rianto — Professional Portfolio

A bilingual (English / Indonesian), responsive static portfolio website built with HTML, CSS, and JavaScript.

## Live website

- Main website: https://ian04kk.github.io/Portofolio-Agus-Rianto/
- English: https://ian04kk.github.io/Portofolio-Agus-Rianto/?lang=en
- Bahasa Indonesia: https://ian04kk.github.io/Portofolio-Agus-Rianto/?lang=id
- English résumé: https://ian04kk.github.io/Portofolio-Agus-Rianto/cv-english.html
- CV Bahasa Indonesia: https://ian04kk.github.io/Portofolio-Agus-Rianto/cv-indonesia.html

## Custom domain

The deployment branch contains a root `CNAME` file for `agusrianto.id`. To use the custom domain, the domain's DNS records must point to GitHub Pages and the custom domain must be verified in **Repository Settings → Pages**. Until DNS is connected and verified, use the GitHub Pages URL above.

## GitHub Pages deployment

The `Publish portfolio files` GitHub Actions workflow publishes the static website from `main` to `gh-pages`. GitHub Pages then builds and deploys the `gh-pages` branch from the repository root.

## Website files

- `index.html` — bilingual home page with language switch and shareable `?lang=en` / `?lang=id` URLs
- `cv-english.html` — printable English résumé; use **Print / Save as PDF** in the browser
- `cv-indonesia.html` — printable Indonesian CV; use **Cetak / Simpan sebagai PDF** in the browser
- `favicon.svg` — site icon using the full name
- `CNAME` — custom-domain declaration on the Pages publishing branch
- `.github/workflows/pages.yml` — automatic publishing workflow

## Accuracy notes

The content is based on the supplied English and Indonesian CV documents. The rooftop solar PV financial and emissions results are identified as a thesis simulation for anonymized PT XYZ. The Ministry of Industry and GIZ research initiatives are labelled as planning-stage work, with their current ToR status stated.
