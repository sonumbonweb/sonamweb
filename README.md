# sonambala.com

Static site, no build step. Every page shares site.css.

- index.html — Work (the default page), with the Mumbai → New Delhi → Bengaluru map
- about.html, bookstack.html, travelogues.html, stumble.html, contact.html
- site.css — the one stylesheet for every page
- photo.jpg — About photo
- work.html — redirects old /work.html links to the homepage
- CNAME — custom domain for GitHub Pages

Book covers load from Open Library (openlibrary.org) when the page is viewed.
If a cover isn't found, the book shows a plain title card instead.

Preview: `python3 -m http.server 8000`, then open http://localhost:8000.
