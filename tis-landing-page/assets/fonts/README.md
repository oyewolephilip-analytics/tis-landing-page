# Fonts

This project loads **Poppins** (headings) and **Inter** (body text) from Google Fonts via a `<link>` in `index.html`.

To self-host instead (fully offline):
1. Download the `.woff2` files for Poppins (500/600/700/800) and Inter (400/500/600).
2. Put them in this folder, e.g. `poppins-700.woff2`, `inter-regular.woff2`.
3. Remove the Google Fonts `<link>` tags from `index.html`.
4. Add `@font-face` rules at the top of `assets/css/style.css`:

```css
@font-face {
  font-family: "Poppins";
  src: url("../fonts/poppins-700.woff2") format("woff2");
  font-weight: 700;
  font-style: normal;
}
```
