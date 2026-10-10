# Ian Pan's website

Personal website at https://ianpan.me, built with Jekyll and the al-folio theme.

## Content

- `_pages/about.md`: homepage and biography
- `_pages/repositories.md`: selected projects, competition solutions, and model demos
- `_bibliography/papers.bib`: publications
- `assets/json/resume.json`: CV entries
- `_config.yml`: site settings, social profiles, and visible CV sections

## Local preview

Run `docker compose up` and open http://localhost:8080. Restart the server after
changing `_config.yml`. The repository includes a Dockerfile and compose files
for the Jekyll environment.

## Deployment

The GitHub Actions workflow in `.github/workflows/deploy.yml` builds the site
when changes are pushed to `main` or `master`. The custom domain is set in `CNAME`.

## Theme

Based on [al-folio](https://github.com/alshedivat/al-folio). See `LICENSE` for the
original theme license. Shared layouts, includes, styles, fonts, and build tools
are retained to support the site.
