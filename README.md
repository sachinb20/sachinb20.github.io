# sachinb20.github.io

Personal academic website of Sachin Bhadang — plain static HTML/CSS, no build step.

- `index.html` — all content (bio, publications, projects, experience)
- `style.css` — styles (light/dark via `prefers-color-scheme`)
- `media/` — profile photo, publication/project thumbnails and videos
- `files/` — CV and PDFs

Preview locally: `python3 -m http.server` and open http://localhost:8000.
To add a paper, copy an `<article class="pub">` block in `index.html`.
