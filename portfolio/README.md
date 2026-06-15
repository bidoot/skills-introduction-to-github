# Personal Portfolio Website

A clean, responsive, single-page portfolio site built with plain HTML, CSS, and JavaScript.
No build tools or frameworks required — just edit and open `index.html`.

## Features

- Responsive layout (mobile-friendly nav menu)
- Light / dark theme toggle (persisted in `localStorage`)
- Smooth scrolling and scroll-reveal animations
- Sections for About, Skills, Projects, and Contact

## Customizing

1. **Your info** — open `index.html` and replace the placeholder content:
   - Name, title, and intro text in the `#home` (hero) section
   - Bio and tech list in the `#about` section
   - Skill categories in the `#skills` section
   - Project cards (title, description, tech tags, GitHub/demo links) in `#projects`
   - Email and social links (`mailto:`, GitHub, LinkedIn) throughout
2. **Styling** — tweak colors, spacing, and fonts via the CSS variables at the top of
   `css/style.css` (`:root` and `[data-theme="dark"]`).
3. **Avatar/photo** — replace the `.avatar-placeholder` initials with an `<img>` tag
   pointing to your own photo if you'd like.

## Running locally

Just open `portfolio/index.html` in your browser, or serve the folder with any static
server, e.g.:

```bash
cd portfolio
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set the source to **Deploy from a branch**.
4. Choose your branch and set the folder to `/portfolio` (or move these files to the
   repo root / a `docs` folder if you'd rather serve from there).
5. Save — your site will be published at `https://<username>.github.io/<repo>/`.
