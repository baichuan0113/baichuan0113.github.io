# baichuan0113.github.io

Personal academic website of Baichuan Li, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and deployed to GitHub Pages via GitHub Actions.

## Editing content

- `_config.yml` - site title, sidebar profile, social links
- `_pages/about.md` - home page
- `_pages/cv.md` - CV page (PDF lives in `files/cv.pdf`)
- `_publications/` - one Markdown file per paper
- `_portfolio/` - one Markdown file per project
- `_data/navigation.yml` - header menu

## Local preview

```bash
bundle install
bundle exec jekyll serve --livereload
```

Then open http://localhost:4000.
