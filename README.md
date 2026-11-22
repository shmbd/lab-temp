# Microbial Biotechnology Division · NIB Bangladesh Website

Official laboratory website repository for the **Microbial Biotechnology Division (MBD)** at the **National Institute of Biotechnology (NIB)**, Savar, Dhaka-1349, Bangladesh, built on the [Greene Lab Website Template (`greenelab/lab-website-template`)](https://github.com/greenelab/lab-website-template).

## Key Features

- **Jekyll + Lab Website Template Architecture**: Modular Markdown pages, YAML data collections, automatic citations pipeline (`_cite/cite.py`), interactive search & tag filtering (`Mark.js`), tooltips (`Tippy.js`), and light/dark mode toggle.
- **MBD · NIB Biotechnology Teal Theme**: Configured in `_styles/-theme.scss` (`#0f7b72` light / `#2dd4bf` dark) with `Barlow` and `Roboto Mono` typography.
- **85 Curated Division Publications (2013–2026)**: Pre-compiled in `_data/citations.yaml` and maintained in `_data/sources.yaml` (with optional automatic ORCID syncing in `_data/orcid.yaml`).
- **Pages & Collections**:
  - `index.md` — Division home page, highlights, recent papers, and metrics
  - `research/index.md` — 4 core research pillars, wet-to-dry lab pipeline, highlighted works, and searchable 85-paper archive
  - `projects/index.md` — Featured shared glycemic-probiotics genome plan (`MBD-SRP-01`) and standing research tracks (`_data/projects.yaml`)
  - `team/index.md` & `_members/*.md` — Individual profiles for 3 Scientific Officers and 7 Research Fellows & Thesis Alumni
  - `join/index.md` — Supervision pathways and FormSubmit inquiry form (`mbddrylab@gmail.com`)
  - `contact/index.md` — Official contact channels and embedded NIB Savar Google Map

## Deployment

### Option 1: GitHub Pages (Included GitHub Actions)
1. Push this repository to GitHub on the `main` branch.
2. In **Settings → Pages**, set **Source** to **Deploy from a branch** and select the `gh-pages` branch (created automatically by `.github/workflows/on-push.yaml`).
3. Every push to `main` automatically runs `_cite` citation checks and builds the live Jekyll site.

### Option 2: Netlify (`netlify.toml` Included)
1. Connect your GitHub repository to Netlify (or link to your existing `mbd-nib` Netlify project).
2. Netlify automatically reads `netlify.toml` (`bundle exec jekyll build` → `_site`) and deploys the site with zero manual setup.

### Local Preview (Requires Ruby 3.x + Bundler or Docker)
```bash
bundle install
bundle exec jekyll serve --open-url --livereload
```
Or with Docker:
```bash
docker build -t mbd-nib-site -f .docker/Dockerfile .
docker run -it -p 4000:4000 -p 35729:35729 -v "%cd%":/usr/src/app mbd-nib-site
```
