# Fiction Grader

A single-page, fully client-side web app (`index.html`). Everything, including the PDF reader, is inlined, so there's no build step and no server code.

## Live site

The site deploys to GitHub Pages on every push to `main`, through `.github/workflows/pages.yml`:

https://ihardlynoah.github.io/ficgrading/

If the first deploy fails, open **Settings → Pages** in the repo and set **Source** to **GitHub Actions**.

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```
