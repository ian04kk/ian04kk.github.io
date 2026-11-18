# Agus Rianto — Professional Portfolio

Bilingual (English / Indonesian), responsive static portfolio website built with HTML, CSS, and JavaScript.

## Live website

- Main website: https://ian04kk.github.io/
- English: https://ian04kk.github.io/?lang=en
- Bahasa Indonesia: https://ian04kk.github.io/?lang=id
- English résumé: https://ian04kk.github.io/cv-english.html
- CV Bahasa Indonesia: https://ian04kk.github.io/cv-indonesia.html

## Hosting and deployment

The website is hosted free on GitHub Pages. No custom domain is configured.

The `Publish portfolio files` GitHub Actions workflow publishes the static website from `main` to the `gh-pages` branch. GitHub Pages is configured to deploy from `gh-pages` at the repository root (`/(root)`).

## Website files

- `index.html` — bilingual homepage with English / Indonesian language switching and shareable `?lang=en` / `?lang=id` URLs
- `cv-english.html` — printable English résumé; use **Print / Save as PDF** in the browser
- `cv-indonesia.html` — printable Indonesian CV; use **Cetak / Simpan sebagai PDF** in the browser
- `favicon.svg` — site icon using the full name
- `.github/workflows/pages.yml` — automatic publishing workflow

## Content accuracy

The portfolio is based on the supplied English and Indonesian CV documents. The rooftop solar PV financial and emissions results are described as a thesis simulation for anonymized PT XYZ. Ministry of Industry and GIZ research initiatives are labelled as planning-stage work, with their ToR status stated.
