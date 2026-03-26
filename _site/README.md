# Personal site (Handsomely Jekyll)

Personal website built with [Handsomely Jekyll](https://github.com/deeneshchowdhary/Handsomely-Jekyll). Light-only theme, no ads.

## Structure

- **Main** — Homepage (filler content; edit `index.html` and `_config.yml`).
- **Projects** — Generated from `_data/projects.yml` (add entries with `title`, `description`, `url`, `role`).
- **Output** — Three sections generated from:
  - `_data/publications.yml`
  - `_data/talks.yml`
  - `_data/posters.yml`

Populate the YAML files and the Projects and Output pages will list the entries automatically.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000. On GitHub Pages, the site builds from this repo automatically.

## Customization

- Site title, description, name, bio, social links: `_config.yml`
- Profile image: replace the placeholder in `_includes/footer.html` with `{{ site.baseurl }}/assets/images/about.jpg` and add `assets/images/about.jpg`
