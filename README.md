# ILI Surveillance Dashboard — Technical Documentation
### Pejabat Kesihatan Kawasan Tawau, Sabah, Malaysia

[![Render Bookdown](https://github.com/YOUR-USERNAME/ili-surveillance-tawau-docs/actions/workflows/render-book.yml/badge.svg)](https://github.com/YOUR-USERNAME/ili-surveillance-tawau-docs/actions/workflows/render-book.yml)

---

## About

This repository contains the technical documentation for the **ILI (Influenza-Like Illness) Surveillance Dashboard** operated by the Epidemiology Unit, PKK Tawau. The documentation is built using [bookdown](https://bookdown.org/) and deployed to GitHub Pages automatically on each push to `main`.

**Live documentation:** https://YOUR-USERNAME.github.io/ili-surveillance-tawau-docs/

---

## Contents

| Chapter | File | Description |
|---|---|---|
| 1 | `index.Rmd` | Background and purpose |
| 2 | `02-data-sources.Rmd` | Data sources and collection methods |
| 3 | `03-methodology.Rmd` | Analytical methodology and threshold derivation |
| 4 | `04-dashboard-guide.Rmd` | Dashboard section-by-section guide |
| 5 | `05-sop-update.Rmd` | Weekly update SOP |
| 6 | `06-interpretation.Rmd` | Interpretation guidance |
| 7 | `07-technical.Rmd` | Technical reference |

---

## Building Locally

### Prerequisites

- R (≥ 4.2.0)
- RStudio (recommended)
- Pandoc (included with RStudio)

### Install R packages

```r
install.packages(c("bookdown", "knitr", "rmarkdown", "kableExtra"))
```

### Render

```r
bookdown::render_book("index.Rmd")
```

Output is written to the `docs/` folder. Open `docs/index.html` in a browser to preview.

---

## GitHub Pages Setup (First-time)

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set Source to **GitHub Actions**
4. Push any change to `main` — the workflow will render and deploy automatically

---

## Update Frequency

Documentation is updated as needed. The dashboard itself is updated **weekly** following each epidemiological week close.

---

## Contact

Epidemiology Unit  
Pejabat Kesihatan Kawasan Tawau  
Sabah, Malaysia
