# br3

Personal site: a landing page, a photo gallery, and a few beats.

**Live:** https://sdaveas.github.io/br3gan/

## Pages

- **`index.html`** — home. Cover photo, plus where to find me (mail, Twitter, GitHub).
- **`gall3ry.html`** — photo gallery. Column toggle (1/2/3), click to zoom, arrow keys to move, Esc to close.
- **`b3ats.html`** — SoundCloud embed of [soundcloud.com/itsthebr3/sets/beats](https://soundcloud.com/itsthebr3/sets/beats).
- **`style.css`** — all styling, shared by the three pages.

## Assets

- `assets/br3gan.png` — cover photo on the home page.
- `assets/photos/` — the nine images the gallery actually serves.
- `thumbs/` — working copies of gallery candidates. No page references them; only a couple are committed.

## Deploying

GitHub Pages, served from `main` at the repo root. No build step and no dependencies — push and it's live.

Deliberately **no `CNAME` file**. `br3gan.com` no longer points here (it's parked at the registrar), so setting a custom domain would just redirect the working github.io URL into a dead domain.

## Notes

- Cover photo credit: `@cjd1884`.
- `scripts/` (untracked) holds the local photo-filtering pipeline used to shortlist gallery candidates. It reads from `~/Photos` and is not part of the published site.
