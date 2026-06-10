# fora-etn.github.io

Archived website of **FORA — Fog Computing for Robotics and Industrial Automation**, an EU Horizon 2020 Marie Skłodowska-Curie European Training Network (grant agreement No 764785) that ran 2017–2021.

This is a static [Jekyll](https://jekyllrb.com/) site served by GitHub Pages. It was migrated from the original WordPress site (`www.fora-etn.eu`) and is preserved as a read-only archive.

## Structure

- `index.md`, `*.md` — content pages (one per original WordPress permalink, set via the `permalink:` front matter)
- `_layouts/default.html` — the single page layout (logo header, nav, EU funding footer)
- `assets/css/style.css` — minimal stylesheet
- `assets/fora-logo.png` — site logo
- `assets/uploads/` — images and documents referenced by the pages
- `wp-content/uploads/` — original-path copies of the PDFs/PPTX so old deep links keep working
- `CNAME` — custom domain (`www.fora-etn.eu`)

## Run locally

```sh
gem install bundler jekyll
jekyll serve
# open http://localhost:4000
```

## Deploy

Push to the `main` branch of `fora-etn/fora-etn.github.io`; GitHub Pages builds and serves it automatically. To use the custom domain, point a `CNAME` DNS record for `www.fora-etn.eu` at `fora-etn.github.io`.
