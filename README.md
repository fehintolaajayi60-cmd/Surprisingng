# Surprisingng — Corporate Gifting Website

A simple static site (HTML/CSS/JS, no build tools) for your corporate gifting proposal — same setup as your personal portfolio site.

## Files
```
index.html        — all page content
css/style.css      — all styling
js/script.js       — footer year
images/logo.jpg    — your Huggers Emporium logo
README.md          — this file
```

## What's clickable
- **Nav "Get a Quote"** and every **"Request a Quote"** button on the 3 package tiers → opens your WhatsApp chat link
- **"Chat on WhatsApp"** (hero + footer) → same WhatsApp chat link
- **"View Our Catalogue"** → your WhatsApp product catalogue
- **Instagram** (footer) → your Instagram profile

If any of these links ever change, just search the file for the old link in `index.html` and replace it — each one appears in 2–3 places (button/nav/footer), so use "Find and Replace" rather than editing one at a time.

## Publish it for free with GitHub Pages
Same process as your personal portfolio:

1. Create a new **public** GitHub repository (e.g. `surprisingng-site`)
2. Upload `index.html`, `README.md`, and the `css`, `js`, and `images` folders — keep the folder structure intact
3. Go to **Settings → Pages**
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`, click **Save**
5. Wait 1–2 minutes, refresh the Pages settings screen, and you'll get a live link like:
   `https://<your-username>.github.io/surprisingng-site/`

That link is what you can share on your gifting proposal PDF, on Instagram, or with any company you reach out to.

## Updating content later
- Package tier details are in the `<!-- PACKAGES -->` section of `index.html`
- Stats (5+ yrs, 16K+, etc.) are in the `<!-- ABOUT -->` section
- To swap your logo, just replace `images/logo.jpg` with a new file of the same name
