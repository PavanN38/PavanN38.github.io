# pavan.dev — Personal Portfolio

A single-file, dependency-free portfolio site for **Pavan Naini**, Senior Full-Stack Developer
(Java · Spring Boot · React · AWS).

No build step, no frameworks — just `index.html` with inline CSS and vanilla JavaScript.
Works straight from `file://` or any static host.

## Features

- Animated particle-network hero with typewriter role rotation
- Scroll-reveal entrance animations (IntersectionObserver, no libraries)
- Animated stat counters, experience timeline, project showcase
- Fully responsive with a mobile slide-in nav
- Dark, recruiter-friendly design

## Run locally

```bash
# any static server works, e.g:
npx serve .
# or
python3 -m http.server 8080
```

## Deploy to GitHub Pages (free)

1. Create a new **public** repo on GitHub named `PavanN38.github.io`
   (a repo with exactly this name becomes your `https://PavanN38.github.io` site).
2. Push this repo to it:

```bash
git remote add origin https://github.com/PavanN38/PavanN38.github.io.git
git branch -M main
git push -u origin main
```

3. Go to **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` → Save.
4. Your portfolio is live at `https://PavanN38.github.io` within a minute or two.

## Customize

Everything lives in `index.html` — content sections are plain HTML,
the theme tokens (`--bg`, `--cyan`, `--violet`, …) are CSS variables at the top of the `<style>` block.
