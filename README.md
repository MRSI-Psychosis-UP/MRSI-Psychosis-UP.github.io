# Psychosis Unit — Lab Website

Static GitHub Pages site for the Psychosis Unit, Department of Psychiatry and
Centre for Psychiatric Neuroscience, CHUV University Hospital of Lausanne.

Single-file site (`index.html`), styled after
https://multiscale-neurodevelopment.github.io/.

## Structure

- `index.html` — the whole site (markup + CSS + small JS for nav/scroll-spy).
- `images/brand/logo.png` — optional logo shown in the header (falls back to
  text if missing).
- `images/brand/orcid.svg` — locally stored ORCID iD icon used by team profile links.
- `images/team/` — team headshots, including `paul_klauser.png`.
- `images/publications/` — publication thumbnails; see the [filename guide](images/publications/README.md).
- `images/general/cover.png` — opening cover image.

## To-do / placeholders to replace

- **Logo**: drop a PNG at `images/brand/logo.png`.
- **Publication thumbnails**: the five papers are listed in `#publications`,
  newest first, with all five thumbnails connected. Image paths are listed in
  [images/publications/README.md](images/publications/README.md).
- **Google Scholar link**: update the `href="#"` on `.scholar-link`.
- **Tools**: the `#tools` section has 2 placeholder cards — point them at
  real repos (e.g. MRSI-Metabolic-Connectome, VLAD, MRSIPrep, DONALD) in the
  [MRSI-Psychosis-UP](https://github.com/MRSI-Psychosis-UP) org.
- **Team photos**: Paul Klauser's photo is connected to
  `images/team/paul_klauser.png`. Other members show initials in a plain box
  (`.avatar`) — swap for an `<img>` once photos are available.
- **About photo**: add a campus/centre photo in the `.about-photo` box.

## Publishing to GitHub Pages

1. Create a repo named exactly `MRSI-Psychosis-UP.github.io` under the
   [MRSI-Psychosis-UP](https://github.com/MRSI-Psychosis-UP) organization.
2. Push this folder's contents to that repo's `main` branch.
3. In the repo Settings → Pages, source should auto-detect as the `main`
   branch root — no `/docs` folder needed.
4. The site will be live at `https://mrsi-psychosis-up.github.io/`.

## Team profile links

The ORCID iD icons beside team names link to the supplied ORCID profiles. Jorge
Alvarez's blue “in” badge links to LinkedIn. Links open in a new tab and have
accessible labels. Daphné Vorburger and Alejandro Rodriguez Guajardo have no
profile link yet. Alejandro is listed as a PhD candidate.

The unmodified ORCID iD icon is stored locally at `images/brand/orcid.svg` and was
downloaded from [ORCID's website](https://orcid.org/assets/vectors/orcid.logo.icon.svg).
See the [ORCID brand guidelines](https://info.orcid.org/brand-guidelines/).
ORCID™ and the iD logo are trademarks of ORCID, Inc.
