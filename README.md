# Tesla Website

A clean, responsive single-page demo of Tesla model landing sections built with HTML, CSS and JavaScript.

This project recreates the look-and-feel of a Tesla model showcase using full-screen background sections, simple CTA buttons, and subtle entrance animations powered by GSAP.

![Demo Screenshot](./Screenshot%202024-09-03%20224915.png)

## Features

- Full-height, scroll-snap sections for Model 3, Model X and Model Y.
- Background images for each section (included in the repo).
- Simple, reusable layout built with semantic HTML and modern CSS.
- Entrance animations using GSAP (CDN included in index.html).
- Responsive: layout and buttons adapt for smaller screens.

## Tech stack

- HTML5
- CSS3
- JavaScript (GSAP for animations)

## Preview

Open `index.html` in your browser to view the site locally. For the best results, serve the folder over a local HTTP server (some browsers restrict local file access for certain assets when opened directly):

```bash
# Optional: serve using Python 3
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

## How it works / Where to look

- `index.html` — main markup with three sections and CTA buttons.
- `style.css` — layout, responsive rules, and background image assignment.
  - Background images are referenced with their file names (e.g. `Model 3.jpg`).
- `script.js` — GSAP timeline that animates headings, links and buttons when the sections load.

To change the background images, replace the files in the repository (`Model 3.jpg`, `Model X.jpg`, `Model Y.jpg`) or update the CSS `background-image` rules in `style.css`.

To adjust animations, edit `script.js` — the site uses a simple GSAP timeline which makes it easy to change durations, easings or add new animated elements.

## File structure

- index.html
- style.css
- script.js
- Model 3.jpg
- Model X.jpg
- Model Y.jpg
- Screenshot 2024-09-03 224915.png

## Contributing

Improvements are welcome. If you'd like to:

- Fix typos or visual bugs — open a PR.
- Add new sections, models, or mobile improvements — open a PR and describe the change.

## License

No license specified. Add a LICENSE file if you want to make the project open-source under a specific license.

---

If you want, I can:
- Add a live GitHub Pages workflow.
- Improve accessibility (focus states, semantic landmarks).
- Optimize images and reduce bundle size.

Tell me which of the above you'd like and I'll make the change.