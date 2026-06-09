# Orinnovative — Static Multi-Page Website

A modern, animated, multi-page website built with pure **HTML, CSS and JavaScript** — no build step required.

## How to run

Just open `index.html` in your browser. That's it.

For best results (so navigation works smoothly), serve the folder with any static server:

```bash
# Python
python3 -m http.server 8080

# Or Node
npx serve .
```

Then visit `http://localhost:8080`.

## Pages

- `index.html` — Home
- `about.html` — About Us
- `services.html` — Services
- `portfolio.html` — Portfolio
- `team.html` — Team
- `blog.html` — Blog
- `contact.html` — Contact (with working demo form)
- `privacy.html`, `terms.html`, `nda.html`, `disclaimer.html` — Legal

## Folder structure

```
orinnovative-html/
├── index.html
├── about.html
├── services.html
├── portfolio.html
├── team.html
├── blog.html
├── contact.html
├── privacy.html
├── terms.html
├── nda.html
├── disclaimer.html
├── css/
│   └── style.css
└── js/
    └── main.js
```

## Features

- Smooth scroll-reveal animations
- Animated stat counters
- Sticky header with scroll effect
- Mobile hamburger menu
- Hover effects on cards, portfolio items and buttons
- Responsive grid layouts (desktop / tablet / mobile)
- Marquee logo strip
- Floating WhatsApp button
- Demo contact form
- Font Awesome icons + Google Fonts (Rubik + Inter)

## Upload to GitHub

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

You can host it for free on GitHub Pages, Netlify, Vercel or Cloudflare Pages — just drag and drop this folder.
