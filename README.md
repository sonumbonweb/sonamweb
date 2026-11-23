# sonambala.com

Static site, no build step. Each page is self-contained: its styles, scripts and images are inside the file.

- index.html — Work (the homepage)
- about.html, bookstack.html, travelogues.html, stumble.html, contact.html
- work.html — sends old /work.html links to the homepage
- CNAME — custom domain for GitHub Pages

Book covers load from Open Library (openlibrary.org) when the page is viewed. If a cover isn't found, the book shows a title card instead.

Preview: run `python3 -m http.server 8000` in this folder, then open http://localhost:8000.
