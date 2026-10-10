# Mariam Amouzoune — Jekyll website

This repository is configured as a Jekyll site for GitHub Pages.

## Structure

- `_config.yml` — site title, description, URL, and project-site base URL.
- `_layouts/default.html` — shared HTML document structure.
- `_includes/header.html` and `_includes/footer.html` — shared navigation and footer.
- HTML pages retain their existing filenames and paths and use Jekyll front matter.
- `main.css` and existing project figures/assets remain in place.

## Local preview

Install Ruby and Bundler, then run:

```sh
gem install bundler jekyll
bundle exec jekyll serve
```

Open the local URL printed by Jekyll. GitHub Pages builds the site from the configured publishing branch and folder.
