# jratchfo.github.io

Jekyll-powered GitHub Pages site for a professional scientific profile.

## Structure

- `_config.yml` - Jekyll and GitHub Pages configuration
- `_layouts/default.html` - shared document shell, navigation, and metadata
- `_posts/` - dated Markdown blog posts
- `assets/css/style.scss` - site styles compiled by Jekyll
- `index.md`, `blog.md`, and `photos.md` - site pages

## Customize

1. Replace publication placeholders and contact links in `index.md`.
2. Add dated Markdown files to `_posts/` using `YYYY-MM-DD-title.md`.
3. Add images to `photos/` and update the gallery in `photos.md`.
4. Update the title and description in `_config.yml`.

## Local development

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

GitHub Pages can build the site directly from the repository's default branch.
