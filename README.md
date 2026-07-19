# Arnav Sinha — Credentials (Industrial Edition)

A subtle industrial/brutalist personal site — inspired by the Cracked Labs aesthetic (monospace data tags, heavy uppercase display type, blueprint grid) in a muted bronze-on-charcoal palette. Plain HTML/CSS/JS, no build step.

## Open it
Double-click `index.html`.

## Pages (top menu)
- `index.html` — **Resume** (home + about + skills)
- `awards.html` — **Awards** (competition honors + impact metrics)
- `research.html` — **Research Papers** (two published papers + Cracked Labs venture)
- `leadership.html` — **Leadership** (organizations, presidencies, outreach)
- `work.html` — **Work** (internships)
- `blog.html` — **Blog** (placeholder posts, ready for your writing)
- `gallery.html` — **Media** (photo gallery, placeholders)
- `contact.html` — **Contact**

## Files
- `css/style.css` — all styling. Theme variables live in `:root`.
- `js/main.js` — mobile menu + scroll animations
- `images/` — put your photos here

## Change the accent color
The muted bronze accent is one variable — edit `--acid` in `css/style.css`:
- Current: `#a98c66` (muted bronze)
- Cooler option: `#7f8a8f` (muted steel)
- Warmer option: `#b08a5c` (tan)
Keep saturation low to stay subtle.

## Add photos
1. Drop images into `images/`.
2. In `gallery.html`, replace a tile's `<div class="ph">…</div>` with `<img src="images/your-file.jpg" alt="description">`.

## Add blog posts
Send me your writing and I'll turn each into a full post page linked from `blog.html`, or wire up a simple markdown workflow so you can publish yourself.

## Publish free
- **Netlify Drop** (app.netlify.com/drop) — drag this folder in, instant URL.
- **GitHub Pages** — upload folder to a repo, enable Pages.
- **Cloudflare Pages** — similar free tier.

---
This is the industrial style. Your original dark-purple version lives in the `site/` folder — same content, different look.
