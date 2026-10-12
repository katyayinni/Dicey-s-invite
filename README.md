# Dicey's Grand Opening: e-invitation

Static website. No build step, no framework, no backend.

## Files
- `index.html`: the whole invitation (HTML, CSS and JavaScript in one file)
- `assets/logo.png`: Dicey's logo with tagline
- `assets/seal.png`: gold wax seal

## Behaviour
- Opens on a sealed envelope. Tapping the seal opens it and the full invitation slides out.
- Live countdown to 16 Oct 2026, 00:00 IST. Change `target` near the bottom of `index.html` to change it.
- "Add to calendar" and Instagram buttons are plain links in the `.actions` section.

## Deploy
Upload the whole folder (keep `assets/` next to `index.html`) to any static host
(Netlify, Vercel, Cloudflare Pages, GitHub Pages, cPanel) and point the domain at it.
For a nicer WhatsApp link preview, add an absolute `og:image` meta tag once the domain is known.
