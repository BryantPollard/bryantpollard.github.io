# bryantpollard.github.io

Personal academic site — graph deep learning research.

## What this is

A single-page static site. Plain HTML

- CSS, no build step, no framework. Just push and GitHub Pages serves it.

## File layout

```
index.html      The whole page
style.css       Styles
README.md       This file
```

## Deploying

1. Drop these files at the root of your `BryantPollard/bryantpollard.github.io`
   repo on the default branch.
2. In the repo on GitHub: **Settings → Pages → Source: Deploy from a branch →
   `main` / `(root)`**.
3. Wait a minute, then visit `https://bryantpollard.github.io`.

## What to customize

Search `index.html` for `TODO` — those are the spots that need your real
content. The main edits:

- Hero block: affiliation, email, Scholar / LinkedIn URLs.
- About: rewrite the three short paragraphs in your own voice.
- Research: keep, edit, or replace the topic list with your actual interests.
- Publications: replace the two placeholder entries.
- News: add real items, most recent first.
- Contact: put in your real email address.

Color, fonts, and spacing live in `style.css` under the `:root` block at the
top — change `--accent` to swap the slate-blue for any other color.

## Notes

- Dark mode works automatically via `prefers-color-scheme`.
- The graph motif in the header is inline SVG — edit node/edge coordinates
  directly in `index.html` if you want a different shape.
- Reduced-motion users won't see the node pulse animation.
