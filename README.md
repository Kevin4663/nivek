# Kevin Hin — Portfolio

A lightweight, static portfolio built with semantic HTML and CSS. Pico CSS is
stored locally in `public/css/`; there is no JavaScript, package manager, or
build step.

## Preview locally

Open `index.html` in a browser, or start Python's built-in static server from
the project folder:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Update the site

- Edit page content and section order in `index.html`.
- Change global colors, typography, spacing, and layout in `styles.css`.
- Update `public/logo.svg` and `public/resume.pdf` to replace those assets.

## Deploy to Vercel

Import the repository into Vercel and deploy it as a static site. No build
command is required; use the repository root as the output directory.

Pico CSS is distributed under the MIT License. See `public/css/LICENSE`.
