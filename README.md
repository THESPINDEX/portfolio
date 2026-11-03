# THESPINDEX

THESPINDEX’s personal portfolio: web development, backend systems, server hosting, automation, and software development.

A responsive static website built with plain HTML, CSS, and JavaScript. No framework, build step, package installation, or backend is required.

[Source code](https://github.com/THESPINDEX/portfolio)

This repository is a public source-code backup. GitHub Pages hosting is disabled.

## Run locally

Open `index.html` in your browser, or serve the folder:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Then visit <http://localhost:4173>.

## Projects

- [Pristine Discord Bot](https://getpristine.xyz/) — Discord moderation, security, verification, tickets, automation, and server management.
- [Daybreak](https://daybreakapp.xyz/) — a fasting and personal development app, currently in beta with frontend and backend development in progress.

## Design and assets

- THESPINDEX appears as a single uppercase name in the hero.
- Real project screenshots are embedded directly in `index.html`; the hero features a centered dog cutout layered over the THESPINDEX signature.
- The dog avatar and favicon are tightly framed and optimized for their display sizes. Both are embedded in the HTML; optional copies are in `assets/`. The supplied photo was reframed with the built-in image tool, preserving the dog’s identity and centering his face against a subdued background.
- Project screenshots are static on hover. Expertise headings turn red on hover or keyboard focus. Reduced-motion preferences are respected.
- Google Fonts supplies Anton and Onest. Lenis is loaded from jsDelivr for optional smooth scrolling; native scrolling remains available when it cannot load.
- No credentials, private server settings, original camera image, or camera metadata are included.

## Editing and hosting

Edit `index.html` directly. The site currently runs locally. GitHub is used for source-code backup only.

## License

The source code is available under the [MIT License](LICENSE). Project names, branding, screenshots, and third-party dependencies remain subject to their respective rights and licenses.

## Hero image

`assets/dog-hero.webp` is an optimized transparent cutout from the supplied dog photo, also embedded in the HTML. It was prepared with the built-in image tool: remove the couch/background, preserve the dog’s pose, expression, fur, tongue and red harness, and center the visible dog with transparent edges. The hero background uses a red radial glow and a subtle CSS grid.
