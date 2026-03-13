# tadeoff.dev

A personal portfolio website styled to look and feel like Visual Studio Code.

The site is fully static (HTML + CSS), lightweight, and easy to host on GitHub Pages or any static web host.

## Overview

This project is a playful portfolio and personal space that includes:

- a VS Code inspired interface
- multiple content pages (about, socials, favorites, and more)
- a custom 404 page for broken routes
- custom domain support via CNAME

## Project structure

```text
.
|- index.html              # Homepage
|- about.html              # About page
|- socials.html            # Social links
|- fav.html                # Favorites page
|- check.html              # Extra content page
|- context.html            # Extra content page
|- photogrammetry.html     # Project/content page
|- 404.html                # Custom not-found page
|- stylesheetVsc.css       # Main shared styles
|- robots.txt              # Search crawler rules
|- CNAME                   # Custom domain for GitHub Pages
`- images/                 # Static assets (icons/images)
```

## Tech stack

- HTML5
- CSS3
- Static assets (images, favicon)

No framework or build tool is required.

## Running locally

Because this is a static site, you can run it in two simple ways.

### Option 1: Open directly

Open index.html in your browser.

### Option 2: Use a local static server (recommended)

Using Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

This repository is ready for static hosting.

### GitHub Pages

1. Push this repository to GitHub.
2. In repository settings, open Pages.
3. Set Source to deploy from your default branch (root).
4. Ensure CNAME matches your custom domain.

## Notes

- Keep links and asset paths consistent across pages.
- For 404.html, root-absolute asset paths are safer for unknown routes.
- The main style file is shared, so most visual changes should go into stylesheetVsc.css.

## License

See LICENSE for details.

**FEEL FREE TO FORK AND ADJUST TO YOUR NEEDS**