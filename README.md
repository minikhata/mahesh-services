# Mahesh Services — website

Company website for **Mahesh Services**, interior & civil contractor and turnkey projects specialist, Sinhagad Road, Pune.

It's a single static page with no build step:

| Path | What it is |
|---|---|
| `index.html` | The whole website (styles and script inline) |
| `img/` | Project photos (stills from the walkthrough video) |
| `project-walkthrough.mp4` | Featured project video |
| `downloads/` | A4 brochure PDF and WhatsApp status image |
| `.github/workflows/pages.yml` | Publishes the site to GitHub Pages on every push to `main` |

## Editing

- **Text & contact details:** edit `index.html` directly.
- **Photos:** drop a new `.jpg` into `img/` and change the matching `src="img/…"` in `index.html`. Original camera photos will look sharper than video stills.
- **Preview locally:** open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

## Publishing

In the repo's **Settings → Pages**, set **Source** to **GitHub Actions** (one time). After that, every push to `main` deploys to:

https://minikhata.github.io/mahesh-services/

## Contact

Mr. Mahesh Tekawade · 96232 97171 / 90283 03709 · maheshservicespune@gmail.com
Near Datta Mandir, Vadgaon Bk., Sinhagad Road, Pune – 411041
