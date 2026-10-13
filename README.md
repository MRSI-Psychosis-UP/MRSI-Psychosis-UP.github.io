# Psychosis Unit — Lab Website

Static GitHub Pages site for the Psychosis Unit, Department of Psychiatry and
Centre for Psychiatric Neuroscience, CHUV University Hospital of Lausanne.

Single-file site (`index.html`), styled after
https://multiscale-neurodevelopment.github.io/.

## Structure

- `index.html` — the whole site (markup + CSS + small JS for nav/scroll-spy).
- `images/brand/logo.png` — optional logo shown in the header (falls back to
  text if missing).
- `images/team/` — optional team headshots.
- `images/general/` — optional figures (e.g. research images).

## To-do / placeholders to replace

- **Logo**: drop a PNG at `images/brand/logo.png`.
- **Publications**: the `#publications` section has 3 placeholder entries —
  replace title/authors/journal/link, and optionally add a thumbnail image
  per entry.
- **Google Scholar link**: update the `href="#"` on `.scholar-link`.
- **Tools**: the `#tools` section has 2 placeholder cards — point them at
  real repos (e.g. MRSI-Metabolic-Connectome, VLAD, MRSIPrep, DONALD) in the
  [MRSI-Psychosis-UP](https://github.com/MRSI-Psychosis-UP) org.
- **Team photos**: each team member currently shows initials in a plain box
  (`.avatar`) — swap for an `<img>` once photos are available.
- **About photo**: add a campus/centre photo in the `.about-photo` box.

## Publishing to GitHub Pages

1. Create a repo named exactly `MRSI-Psychosis-UP.github.io` under the
   [MRSI-Psychosis-UP](https://github.com/MRSI-Psychosis-UP) organization.
2. Push this folder's contents to that repo's `main` branch.
3. In the repo Settings → Pages, source should auto-detect as the `main`
   branch root — no `/docs` folder needed.
4. The site will be live at `https://mrsi-psychosis-up.github.io/`.
