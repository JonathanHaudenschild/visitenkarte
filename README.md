# Visitenkarte

A digital business-card concept created with HTML and SCSS. The design recreates
an illustrated character, face mask, and headphones entirely with CSS and presents
contact links on the reverse side.

The page also embeds the original Figma design for comparison.

## View locally

Clone the repository and open `index.html` in a browser. No build step is required
because the compiled `style.css` is included.

For a local web server, you can run:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Editing the styles

The source styles are in `style.scss` and `variables.scss`. After making changes,
compile them with any Sass implementation, for example:

```bash
sass style.scss style.css
```

## Files

- `index.html` — card markup, social links, and embedded Figma preview
- `style.scss` — source styles and CSS illustration
- `variables.scss` — shared color values
- `style.css` — compiled styles used by the page
- `VisitenKarten_Eigens(figma).pdf` — exported design reference

## Status

This is a small design experiment from 2021 and is kept as a portfolio/archive
project.
