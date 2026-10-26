# Visualizing Science Concepts

Interactive visuals for the science classroom (Alberta K-12), served with GitHub Pages.
It is set up the same way as the math site, [shawnlemko/mathvisuals](https://github.com/shawnlemko/mathvisuals).

- `index.html` is the main page: a grid of tool tiles with grade tabs (K-6, 7-9, 10-12), topic tabs and search. The topics are the organizing ideas of Alberta's K-9 science curriculum.
- Each tool is one self-contained HTML file next to it, with a "Return to Main Page" button that links to `index.html`.
- `.nojekyll` tells GitHub Pages to serve the files as they are.
- Every page has the GoatCounter analytics script in its `<head>`.

## Add a tool

1. Put the tool's HTML file in this folder, starting with the same `<head>` block as `solubility.html` (it holds the analytics script).
2. In `index.html`, copy one `<li>` inside `<ul class="concepts">` and change `href`, the picture, the name, the note,
   `data-bands` (`K-6`, `7-9`, `10-12`, space-separated) and `data-cat` (`mat` Matter, `ene` Energy, `ear` Earth Systems, `liv` Living Systems, `spa` Space, `cs` Computer Science, `sm` Scientific Methods).
   A tile that fits a second topic can also list it in `data-also` (space-separated); its colour still comes from `data-cat`.

## Tools

| File | Tool | Grades, topic |
| --- | --- | --- |
| `solubility.html` | Solubility and Precipitates | 10-12, Matter |
| `heating-curve.html` | Heating Curve of Water | 10-12, Energy (also Matter) |
| `ionic-builder.html` | Ionic Formula Builder | 10-12, Matter |
| `unit-analysis.html` | Unit Analysis | 7-9 and 10-12, Scientific Methods |
