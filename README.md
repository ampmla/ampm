# AMPM Studio Website

A production-ready bilingual static website for **AMPM Studio** in English and Korean.

## Files

- `index.html` — complete page structure and SEO metadata
- `css/style.css` — responsive styling, bilingual typography, layout, and animations
- `js/script.js` — mobile navigation, sticky header state, active nav state, smooth UX interactions
- `public/favicon.svg` — simple favicon placeholder
- `.gitignore` — common local ignore rules

## Features

- Bilingual English + Korean content
- Sticky responsive navigation
- Mobile hamburger menu
- Smooth scrolling
- Active navigation state on scroll
- Fade-up reveal animations via `IntersectionObserver`
- Keyboard accessible navigation and skip link
- SEO metadata and Open Graph tags
- Responsive layout for mobile, tablet, and desktop
- Desktop content width capped at `1200px`

## Run locally

Because this is a static site, you can open `index.html` directly in a browser or serve it locally.

### Option 1

Open `index.html` in your browser.

### Option 2

Serve with a local static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes

- Replace `https://example.com` in `index.html` with the real production URL.
- Replace `public/og-placeholder.jpg` with a real social sharing image if desired.
- Contact email is `ampmdaypro@gmail.com`.
