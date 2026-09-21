# Personal Portfolio Website (Assignment 1)

A responsive personal portfolio built with **HTML and CSS only** (no JavaScript, no framework).

## Sections
Home, About me, Skills (table), Projects, Contact (form).

## Run it
Open `index.html` in a browser, or run `python -m http.server 8000` in this folder and visit http://localhost:8000.

## Folder structure
```
portfolio-website/
├── index.html          All five sections
├── css/style.css       External stylesheet (Flexbox layout, responsive rules)
├── images/             Profile image, favicon, project screenshots
├── screenshots/        Desktop, tablet and mobile screenshots for the submission
└── docs/               Assignment report (PDF)
```

## Make it yours (5 minutes)
1. **Photo:** put your photo in `images/` (for example `profile.jpg`), then change `images/profile.svg` in `index.html` to `images/profile.jpg`.
2. **Email:** search `index.html` for `youremail@example.com` and replace it (two places).
3. **Project links:** search for `TODO` in `index.html` and paste the real links for the store and this portfolio.
4. **Name and text:** edit the About me and Skills text so every sentence is true for you.

## Techniques used
Flexbox layout, CSS variables, box model (`box-sizing: border-box`), media queries (900, 760 and 640 px), a CSS-only mobile menu, a responsive table, hover effects and transitions, and `prefers-reduced-motion` support.

## Publish it (optional live demo)
Push the folder to a GitHub repository, then **Settings, Pages, Deploy from a branch, main, / (root)**.
