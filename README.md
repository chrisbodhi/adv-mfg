# Adaptive Manufacturing Systems: Theory and Practice

A graduate interdisciplinary seminar syllabus exploring adaptive manufacturing—production systems designed for reconfiguration, resilience, and distributed coordination.

**Live site:** https://chrisbodhi.github.io/adv-mfg/

## Local development

Requires [Zola](https://www.getzola.org/):

```
brew install zola
zola serve
```

## Build

```
zola build
```

Output goes to `public/`.

## Deployment

Pushes to `main` trigger GitHub Actions to build and deploy to GitHub Pages.

## Content

The syllabus lives in two places:

- `syllabus.md` — plain markdown for easy reading
- `content/_index.md` — same content with Zola front matter

Edit `syllabus.md` as the source of truth, then sync changes to `content/_index.md`.

## Styles

The site uses the Tomorrow's Horizon design system. See `sync-styles.md` for how to update styles from `style-guide.html`.
