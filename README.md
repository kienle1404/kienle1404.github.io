# kienle1404.github.io

Personal academic website. Plain HTML/CSS with no build step, hosted on GitHub Pages.

## Files

| File | What it is |
|---|---|
| `index.html` | All page content |
| `style.css` | Layout and colors |
| `images/` | Profile photo and favicon |
| `files/cv.pdf` | CV linked from the page |
| `404.html` | Shown for broken links |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Preview

Double-click `index.html` to open it in a browser.

## Common updates (all in `index.html`)

- **News:** copy one `<li>` in the News list and paste it at the top. Only the newest 5 show; older ones collapse automatically.
- **Paper:** copy one `<li class="pub">` block in Publications. Update the badge (e.g. `NeurIPS'27`), title, authors, venue, and links. Keep your name in `<strong>`.
- **Research position / project:** copy one `<div class="entry">` block.
- **CV:** replace `files/cv.pdf` (keep the same name).
- **Photo:** add `images/profile.jpg` (square, ~400×400) and change the `<img src>` in the header.
- **Footer:** bump "Last updated".

## Publish

```
git add -A
git commit -m "Update news"
git push
```

The live site updates in about a minute.
