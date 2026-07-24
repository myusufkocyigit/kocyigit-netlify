# yusufkocyigit.me

Source for Muhammed Yusuf Kocyigit's personal research website.

The site uses Jekyll and the MIT-licensed [al-folio](https://github.com/alshedivat/al-folio) academic website theme.

## Local development

Use Ruby 3.3 and Bundler 4, then install the dependencies and start Jekyll:

```bash
bundle install
bundle exec jekyll serve
```

Build the production site with:

```bash
JEKYLL_ENV=production bundle exec jekyll build
```

Netlify builds the site from `netlify.toml` and publishes `_site`.
