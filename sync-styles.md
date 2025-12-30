# Style Sync Guide

The styles in `static/style.css` are derived from `style-guide.html` (Tomorrow's Horizon design system).

## What's extracted

From `style-guide.html`, we use:
- CSS custom properties (`:root` variables) - colors, typography, spacing
- Base element styles (body, headings, lists, links, hr)
- Google Fonts: Anybody (display) + Source Serif 4 (body)

## To sync after updating style-guide.html

1. Open `style-guide.html` and locate the `<style>` block
2. Copy the `:root` variables section to `static/style.css`
3. Update any base element styles that have changed
4. Check Google Fonts link in `templates/index.html` matches the style guide
5. Run `zola build` and verify in browser

## Design tokens reference

| Token | Value | Use |
|-------|-------|-----|
| `--cream` | #FAF7F0 | Page background |
| `--midnight` | #1A1A2E | Headings, emphasis |
| `--ink` | #2D2D44 | Body text |
| `--atomic-orange` | #E85D04 | Primary accent |
| `--stellar-teal` | #00A8A8 | Links, secondary accent |
| `--font-display` | Anybody | Headings |
| `--font-body` | Source Serif 4 | Body text |
