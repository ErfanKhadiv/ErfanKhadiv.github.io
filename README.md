# Erfan Khadiv, portfolio website

Personal portfolio: HBALS research on the Traveling Salesman Problem, selected projects, skills, education, certificates, a short internship story and contact.

It is a plain static site (HTML, CSS and a little JavaScript). There is no build step and nothing to install.

## Files

- `index.html`: the whole page
- `assets/img/`: thumbnails, certificates and photos

## Publish with GitHub Pages

1. Create a new public repository on GitHub. Naming it `ErfanKhadiv.github.io` puts the site at `https://erfankhadiv.github.io/`. Any other name puts it at `https://erfankhadiv.github.io/<repo-name>/`.
2. Upload every file from this folder, keeping `index.html` at the top level of the repository and the `assets` folder next to it.
3. Open Settings, then Pages. Under Build and deployment choose "Deploy from a branch", select the `main` branch and the `/ (root)` folder, then save.
4. After a minute the site is live. Add the link to your CV, GitHub profile and LinkedIn.

## Preview locally

Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit `http://localhost:8000`.

## Notes

- The animated map at the top runs HBALS, a JavaScript port of the Python implementation in [HBALS-TSP](https://github.com/ErfanKhadiv/HBALS-TSP) (fast preset). Visitors can pick one of six TSPLIB instances (eil51, berlin52, st70, kroA100, ch150, rat195) or random cities, and tap the map to add their own. TSPLIB instances use rounded Euclidean distances, as in the benchmark; random and added cities use exact distances. The instance coordinates are embedded in `index.html` (search for `const DATA=`). Source: Reinelt, TSPLIB, 1991.
- Results vary from run to run because the search is random, so the page shows the best result seen this session next to the best-known length.
- Photos added: `ielts_van.jpg` (the highlighted British Council sign is positioned with percentages in the `.pin .ring` CSS rule) and `lab_scope.jpg`, `lab_breadboard.jpg` (Electrical Circuits Laboratory).
- Fonts load from Google Fonts. If they are blocked the page falls back to system fonts.
- To change a link, search `index.html` for its URL. The contact buttons are listed near the bottom of the file, in the `LINKS` list.
- Theme and language: the page opens in dark mode and English. The sun/moon button switches between dark and light, and the FA/EN button switches between English and Persian (right-to-left). Both choices are remembered in the visitor's browser (localStorage).
- Persian text: every translatable element in `index.html` has a `data-t="N"` attribute, and the Persian strings are in the `FA` array near the bottom of the file (item N is the translation of element `data-t="N"`). Image descriptions and aria-labels are in the `ATTR` object next to it, keyed by the English text. The Persian font (Vazirmatn) is only loaded from Google Fonts when Persian is selected. Numbers stay in Latin digits. To change a sentence, edit the English in the HTML and the matching entry in `FA`.
- Icons: `icon.svg` (modern browsers), `favicon.ico`, `apple-touch-icon.png` (iPhone/iPad home screen) and `icon-192.png` / `icon-512.png`. Keep them in the top-level folder next to `index.html`.
- In Persian mode dates are shown in the Persian (Solar Hijri) calendar, and the footer year too.
- The top menu is sticky with a frosted-glass look (`nav.glass`), and a round back-to-top button (`#totop`) appears at the bottom right after scrolling.
- The menu item of the section you are viewing is highlighted (yellow, bolder, slightly larger). Style: `nav.glass .navin a.active`.
