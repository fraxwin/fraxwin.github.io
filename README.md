# Academic homepage — Franziska Windisch

A four-page static site (About, Research, Teaching, CV) with a fixed left panel.
No build step — plain HTML/CSS. Type is Source Serif 4, loaded from Google Fonts.
Content is filled in from your CV; only a few links and files remain to add.

## Files

```
index.html          About / landing page
research.html       research themes, working papers, work in progress
teaching.html       courses
cv.html             CV summary + link to PDF
assets/css/style.css      all styling (one file)
assets/img/headshot.jpg   <-- replace with your photo (square works best)
assets/cv.pdf             <-- add your CV PDF here
```

## What's left to fill in (search for `data-todo` and the note box)

1. Sidebar links (all pages): add your real Google Scholar and ORCID URLs
   (currently `#`). The email is already set to franziska.windisch@univie.ac.at.
2. research.html: the Smartvote Austria link (`data-todo="smartvote"`).
3. cv.html: drop your CV PDF at `assets/cv.pdf`, then delete the note box.
4. assets/img/headshot.jpg: replace the placeholder with your photo.

Everything else — bio, research themes, working papers, teaching, talks — is
already written from your CV. Edit any wording you'd like to change directly in
the HTML.

## A note on what's deliberately NOT on the site

Your CV and application letter contained private details that don't belong on a
public page: home address, phone number, date of birth, student/registration
numbers, exact grades, and anything about the FH Campus Wien application. None of
that is in these files. The site reflects your current role in Vienna only.

## Colour

The accent (a muted academic brown) is set once at the top of `style.css`:

```css
--accent:   #6b4f2e;
--accent-h: #8a6a41;
```

Change those two values to recolour every link and active-nav marker.

## The left panel

It's repeated in each HTML file (no build step). If you change a sidebar link,
update it in all four files — a find-and-replace across the folder does it once.

## Publish on GitHub Pages

1. Create a repo named **`<your-username>.github.io`** (site goes live at
   `https://<your-username>.github.io`).
2. Upload the contents of this folder to the repo root.
3. Settings → Pages → Source: Deploy from a branch, branch `main`, folder
   `/ (root)`. Save.
4. Wait ~1 minute, then visit your URL.

We can do these steps together with Claude Code once you're ready.
