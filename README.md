# stuffbykyle

A one-page landing site linking to everything I've built. Plain static HTML, no build step:
`index.html`, `favicon.svg` and one illustrated thumbnail per project in `thumbs/`.

Preview locally with any static server, e.g. `python3 -m http.server` and open http://localhost:8000.

On Railway, Railpack sees `index.html` at the root and serves the folder as a static site.

To add a project, copy one of the `<a class="card">` blocks in `index.html` and drop an 800×500
thumbnail (SVG, PNG or JPG) into `thumbs/`.
