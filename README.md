# Aya Elsayed — Financial Journalism Portfolio

Responsive, lightweight portfolio website for Aya Elsayed, a Cairo-based financial journalist and senior English economic analyst.

## What is included

- Readable white-and-blue professional theme, using the operating system's sans-serif font stack.
- Accessible, responsive homepage with contact actions near the top.
- Professional profile and **Egypt + GCC regional perspective**.
- Filterable and searchable selection of **FirstBank** banking coverage and **Amwal Al Ghad English** stories.
- Each story has a **local summary** page and a **direct link** to the original published article.
- A portable CSV catalogue, plus machine-readable JSON metadata.
- Career history and academic background.

## Public website

If GitHub Pages has been enabled, the project URL is:

https://ayaseldein.github.io/aya-salah.github.io/

To publish: **Settings → Pages → Build and deployment → Source → GitHub Actions**. Every push to `main` triggers the workflow in `.github/workflows/deploy.yml`.

## Archival limits

The repository contains **locally preserved source metadata and independently written summaries**; it does not include complete copies of publisher articles or their images. See `archive/README.md` for instructions on adding original drafts or republication-authorised complete texts to create true full-text backups.

## Editing

- `index.html`: all landing-page content, styles, interactions.
- `story.html`: local article detail page.
- `archive/articles.json`: source data for article cards and detail pages.
- `archive/article-index.csv`: independent downloadable archive catalogue.
- `archive/README.md`: archive and authorship notes.

No build tools, npm packages or external font libraries are required. Online GitHub Pages deployment needs GitHub Actions enabled.

## Editorial credits

Verified Amwal Al Ghad bylines are described as such. FirstBank stories are labelled publication coverage rather than asserting individually verified authorship.
