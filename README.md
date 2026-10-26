# Visualizing Science Concepts

Interactive visuals for the science classroom (Alberta Science 10 and Chemistry 20), served with GitHub Pages.
It is set up the same way as the math site, [shawnlemko/mathvisuals](https://github.com/shawnlemko/mathvisuals).

- `index.html` is the main page: a grid of tool tiles with course tabs, topic tabs and search.
- Each tool is one self-contained HTML file next to it, with a "Return to Main Page" button that links to `index.html`.
- `.nojekyll` tells GitHub Pages to serve the files as they are.
- Every page has the GoatCounter analytics script in its `<head>`.

## Add a tool

1. Put the tool's HTML file in this folder, starting with the same `<head>` block as `solubility.html` (it holds the analytics script).
2. In `index.html`, copy one `<li>` inside `<ul class="concepts">` and change `href`, the picture, the name, the note,
   `data-bands` (courses: `Sci 10`, `Chem 20`) and `data-cat` (`chem`, `phys`, `bio`, `earth`).

## Tools

| File | Tool | Courses |
| --- | --- | --- |
| `solubility.html` | Solubility and Precipitates | Science 10, Chemistry 20 |
