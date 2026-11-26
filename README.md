# Udy

Interactive portfolio page for Uddipan Doley, Marketing Leader.

Two versions:

- `index.html`: Marketing Leader version (with the Portcast role-fit section).
- `b2b-tech/index.html`: B2B Technology Marketing Leader version, no role-specific section. Served at `https://chaosaddict666.github.io/Udy/b2b-tech/`.

Open either file in a browser. It is a single self-contained file: fonts load from Google Fonts, and all logos and icons are embedded.

## Editing

- **Portcast role-fit section:** it is written for one application. To remove it, delete the `<div class="band" id="fit">` block and the "Portcast fit" link in the top menu.
- **Role-fit scores:** edit the `FIT` array in the script near the bottom of the page.
- **Toolkit:** edit the `TOOLS` array.
- **Company logos:** stored as data URIs in `LOGO_FILES`.

## Publish with GitHub Pages

Settings → Pages → Deploy from a branch → `main` / root. The page will be served at `https://chaosaddict666.github.io/Udy/`.
