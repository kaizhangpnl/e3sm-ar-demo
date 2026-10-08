# EAMxx atmospheric river demo

Plain HTML/CSS pages for atmospheric-river figures, case-study movies, and related links.

Hosted at: https://kaizhangpnl.github.io/e3sm-ar-demo/index.html 

## Files

- `index.html` — Home. The introduction links to the figure and movie pages.
- `figures.html` — displayed as **Figures** in the navigation. Lists the three figure pages.
- `frequency.html`, `regional.html`, `duration.html` — one figure category each. The plots are in `figures/`.
- `tools.html` — displayed as **Movies** in the navigation. Lists the four case-study pages.
- `movie-north-pacific.html`, `movie-north-atlantic.html`, `movie-southeast-pacific.html`, `movie-south-atlantic.html` — one case study each. The animations are in `movies/`.
- `resources.html` — displayed as **Resources** in the navigation
- `about.html` — optional About page (not shown in the four-item navigation)
- `css/style.css` — shared styling
- `.nojekyll` — tells GitHub Pages to serve the files directly without Jekyll processing

## Publish with GitHub Pages

1. Create a GitHub repository, for example `arm-for-modelers`.
2. Upload the contents of this folder to the repository root.
3. Commit the files.
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)` folder, then save.

For a project repository named `arm-for-modelers`, the site will normally be published at:

`https://YOUR-USERNAME.github.io/arm-for-modelers/`

All internal navigation uses relative links, so the site works correctly from a GitHub Pages project path.

## Visual design

Shared styling in `css/style.css`:

- warm paper background (`#f6f4f0`) and a compact sticky header;
- left-aligned page titles in Open Sans, with a short teal rule (`#3d7684`, 40×3px);
- charcoal text (`#2c2825`) and a muted caption color;
- orange accent for external links (`#c2603d`);
- Open Sans for body text and titles;
- the Home / Figures / Movies / Resources navigation and dot separators;
- responsive behavior for tablets and phones.

## Editing content

Update page content directly in the HTML files. Most visual changes can be made once in `css/style.css` and will apply to every page.
