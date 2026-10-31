# Zuge Li's academic homepage

Live at <https://mowon0303.github.io/>. Built with [Academic Pages](https://github.com/academicpages/academicpages.github.io), a fork of [Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/).

## Editing

| To change | Edit |
| --- | --- |
| Home page text | `index.html` |
| Updates list | `_data/updates.yml` |
| Projects | `_data/projects.yml` |
| Publications | one file per paper in `_publications/` |
| CV page | `_pages/cv.md` |
| Name, bio, and sidebar links | `_config.yml` |
| Top navigation | `_data/navigation.yml` |
| Photo | add it to `images/`, then set `author.avatar` in `_config.yml` |
| Colors | `_sass/theme/_paper_light.scss` and `_sass/theme/_paper_dark.scss` |
| Layout and spacing | `_sass/layout/_paper.scss` |

Pushing to `main` rebuilds and deploys the site through `.github/workflows/jekyll.yml`.

## Preview locally

Requires Ruby 3.1 or newer and Node.js.

```bash
bundle install
npm install
npm run build:js
bundle exec jekyll serve
```
