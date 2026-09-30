# Ananya Appan — Personal Website

A minimal Jekyll site. No theme gem — everything is in this folder.

## Run locally

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Customize

| What | Where |
|---|---|
| Name, email, links, nav | `_config.yml` |
| Bio / home page | `index.md` |
| Profile photo | `files/anu_recent.jpeg` (`author.photo` in `_config.yml`) |
| Publications (Research page) | `_data/publications.yml` |
| Teaching | `teaching.md` |
| CV | replace `files/anu_CV.pdf` |
| Styling | `assets/css/style.css` |

## Deploy to GitHub Pages

Copy these files into the `AnanyaAppan.github.io` repo and push. GitHub Pages builds it automatically.
