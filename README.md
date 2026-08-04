# Academic homepage — Franziska Windisch

A four-page static site (About, Research, Teaching, CV) with a fixed left
panel. Plain HTML/CSS, no build step. Type is Source Serif 4 (Google Fonts).

## Files

```
index.html          About / landing page
research.html       working papers + work in progress (with abstracts)
teaching.html       courses with syllabus links
cv.html             CV page with the PDF embedded inline + download link
assets/css/style.css   all styling
assets/img/headshot.jpg   the photo
assets/cv.pdf          the CV PDF (embedded on the CV page)
```

## Publishing / updating on GitHub Pages

The site lives at https://fraxwin.github.io from the repo
`fraxwin/fraxwin.github.io`.

To update: upload a changed file to the SAME path it already has in the repo
(GitHub's uploader drops files into whichever folder you're viewing, so open
the target folder first). For example, to update the stylesheet, go into
`assets/css/` and upload `style.css` there; to update a page, upload it to the
repo root.

IMPORTANT — folder paths must match exactly:
- `style.css`  -> assets/css/
- `headshot.jpg` -> assets/img/
- `cv.pdf`     -> assets/  (directly, not in a subfolder)

If the site ever shows unstyled text or a missing photo, it's almost always a
file sitting in the wrong folder — check the three paths above.

## To change things later

Everything is plain HTML — open a file on GitHub, click the pencil, edit, and
commit. The live site updates within a minute.
