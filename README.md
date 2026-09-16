# amrutp24.github.io

Source for [amrutp24.github.io](https://amrutp24.github.io/), the personal site of Amrut Pagidipally.

One static HTML file. No build step, no framework, no dependencies beyond one webfont (Newsreader, from Google Fonts).

- `index.html` — the whole site: markup, styles, and a few lines of script for the light/dark toggle
- `404.html` — not-found page
- `images/og.png` — link-preview card; `images/icon-180.png` — touch icon
- `.nojekyll` — tells GitHub Pages to publish the files as-is instead of running Jekyll

Edit `index.html` and push to `main`; GitHub Pages publishes it within a minute.

To preview locally, open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```
