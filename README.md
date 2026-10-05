# Communication Theory Website (Jekyll + GitHub Pages)

This repository is set up as a Jekyll site for GitHub Pages in the `Jacobw23-Coder/primer` project. The current structure provides accessible page scaffolding and starter content you can replace with your own analysis.

## Site structure

- `_config.yml` — site settings (title, URL, base path, metadata)
- `_layouts/default.html` — shared page layout and navigation
- `assets/css/style.css` — color palette and visual styling
- `index.md` — home page
- `pages/` — six required subpages
- `images/` — place your uploaded visuals here
- `.github/workflows/jekyll.yml` — GitHub Actions workflow for build/deploy on push to `main`

## Add and edit content

1. Edit `index.md` to update your project introduction.
2. Edit each file in `/pages` with your final analysis:
   - `transmission-view-and-limits.md`
   - `meaning-and-culture.md`
   - `interpretation-and-power.md`
   - `interpretation-and-intention.md`
   - `what-the-reader-should-do.md`
   - `how-i-built-this-site.md`
3. Keep front matter at the top of each file (`layout` + `title`) so pages render with the site template.
4. Add images to `/images` and reference them in markdown with:

   ```md
   ![Alt text]({{ '/images/your-file-name.jpg' | relative_url }})
   ```

## Local preview

From the repository root:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000/primer/` for local preview (project site base path).

## GitHub Pages and workflow behavior

- Workflow file: `.github/workflows/jekyll.yml`
- Trigger: every push to `main` (plus manual trigger)
- Jobs:
  - Build with Jekyll
  - Upload artifact
  - Deploy to GitHub Pages

## Basic design customization

Edit `assets/css/style.css` and adjust variables in `:root`:

- `--forest-green`
- `--moss-green`
- `--stone-gray`
- `--mist-gray`
- `--muted-brown`
- `--bark-brown`
- `--paper`
- `--ink`
- `--focus`

You can customize typography, spacing, or navigation styles in the same file while keeping accessibility features intact.

## Accessibility features included

- Semantic landmarks (`header`, `nav`, `main`, `footer`)
- ARIA labels on key regions
- Keyboard-friendly skip link
- Focus-visible outlines for keyboard users
- High-contrast text/background combinations

## Notes on authorship and scaffolding

The structure, boilerplate layout, workflow setup, and starter text were scaffolded with help from a Copilot task agent. You should replace/expand the analytical content with your own final argumentation, examples, and citations.
