# Hamid Adewuyi — personal website

A retro clip-art desktop site with Orbit, a rolling globe guide who greets visitors and walks them through each section.

Everything lives in one file, `index.html`: no framework, no build step, no dependencies beyond Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Editing

- **Blog posts:** add or edit entries in the `POSTS` array in the script at the bottom of `index.html`. Set `draft: true` to show a Draft tag instead of a date.
- **Orbit's lines:** edit the `S` object in the same script.
- **Colours and fonts:** the tokens are in the `:root` block at the top of the stylesheet.

## Hosting

Turn on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root) and the site is served at https://dayo-adewuyi.github.io/profile/.
