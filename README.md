# Agus Rianto — Professional Portfolio

Bilingual English / Indonesian professional website, built as a regular static HTML, CSS and JavaScript site.

## Target public URL

https://agusrianto.id/

## Custom domain: agusrianto.id

The publishing source includes a root `CNAME` file for `agusrianto.id`. Configure the DNS records at the domain registrar, then verify the custom domain under GitHub Pages settings.

## Enable GitHub Pages

1. Open [Repository Settings → Pages](https://github.com/ian04kk/Portofolio-Agus-Rianto/settings/pages).
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **gh-pages** and folder **/(root)**, then click **Save**.

GitHub Actions automatically publishes the site files from `main` to the `gh-pages` branch whenever `main` changes.

## Files

- `index.html` — bilingual homepage
- `cv-english.html` — English résumé; use Print / Save as PDF
- `cv-indonesia.html` — Indonesian CV; use Cetak / Simpan sebagai PDF
- `favicon.svg` — full-name site icon
- `downloads/` — original CV files
- `.github/workflows/pages.yml` — publishing workflow

Project statements and status labels are based on the supplied CV. The solar PV thesis is a simulation; the Kemenperin and GIZ initiatives are labelled as planning-stage work.
