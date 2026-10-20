# Hantian Zhang — Academic Homepage

Personal academic website built with [Academic Pages](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub Pages at <https://zht2005.github.io/>.

## Update the site

- Edit `_pages/about.md` for the introduction and selected work.
- Edit `_pages/research.md` for research experience.
- Edit `_pages/publications.md` for publications and manuscript status.
- Edit `_pages/cv.md` for the CV summary; replace `files/Hantian_Zhang_CV.pdf` when the PDF changes.
- Edit `_config.yml` for the sidebar and contact details, and `_data/navigation.yml` for the menu.

Changes pushed to `master` deploy through `.github/workflows/jekyll.yml`.

## Local build

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000/>.
