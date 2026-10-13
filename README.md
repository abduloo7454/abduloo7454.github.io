# main-site

Personal academic homepage for Abdullah. Plain HTML and CSS, no build step.

## Files

- `index.html` is the homepage (bio, featured publication cards, updates).
- `publications.html` is the full publication list.
- `style.css` holds the styles shared by both pages.
- `images/profile.jpg` is the square headshot cropped from the original photo.
- `.nojekyll` stops GitHub Pages from running Jekyll on this folder.

## Preview locally (run on your Mac)

```bash
cd "/Users/abdullahabdullah/Documents/Personel Website/main-site"
python3 -m http.server 8000
# then open http://localhost:8000
```

## Publications source

Titles, authors, venues and links come from the Google Scholar profile
(user e6CxHyAAAAAJ), checked on 13 Oct 2026. IEEE titles were checked against IEEE Xplore.
When a new paper appears, add a `<div class="pub">` block in publications.html, an `<article class="card">` in index.html if it should be featured, and an update line.
