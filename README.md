# ARM For Modelers — GitHub Pages starter site

This is a plain HTML/CSS package hosted at: https://kaizhangpnl.github.io/arm-for-modelers/index.html 

## Files

- `index.html` — Home
- `figures.html` — displayed as **Figures** in the navigation. The three plots are in `figures/`.
- `tools.html` — displayed as **Movies** in the navigation. The four case-study animations are in `movies/`.
- `resources.html` — displayed as **Resources** in the navigation
- `about.html` — optional About page (not shown in the four-item navigation, to match the reference screenshots)
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

The CSS reproduces the reference design with:

- white background and compact top navigation;
- centered teal page headings (`#3d7684`) with a short teal rule;
- dark charcoal text (`#332d2a`);
- orange accent links/rules (`#c2603d`);
- warm gray section separators (`#dad1c7`);
- Arial for body content and Open Sans for the site/page titles;
- the Home / Figures / Movies / Resources navigation and dot separators;
- responsive behavior for tablets and phones.

## Editing content

Update page content directly in the HTML files. Most visual changes can be made once in `css/style.css` and will apply to every page.
