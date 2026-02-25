Personal website for Alba Vazquez García

Overview
--------
This repository contains the static personal website for Alba Vazquez García. It is a simple HTML/CSS site with three main pages:

- `index.html` — Home / profile
- `research.html` — Research and working papers
- `teaching.html` — Teaching and course information

Local preview
-------------
You can preview the site locally using any static file server. For example, with Python 3 run:

```bash
python -m http.server 8000

# then open http://localhost:8000 in your browser
```

Editing
-------
- Site files are plain HTML with embedded CSS. Edits can be made directly to the `.html` files.
- Keep styles consistent across pages by updating the inline `<style>` blocks in each file.

Deployment
----------
This repository is intended to be hosted on GitHub Pages. Push changes to the `main` branch and the site will publish at `https://albavazquezgarcia.github.io/` (verify Pages settings in the repository if needed).

Notes
-----
- Fonts: the site uses Arial as the primary font with fallbacks to Helvetica and generic sans-serif.
- Email address is included as a `mailto:` link on the home page.

If you'd like, I can:

- Extract shared styles into a single `styles.css` file and update pages to reference it.
- Add a simple build or deployment script.
- Improve accessibility (contrast, headings, ARIA attributes).

