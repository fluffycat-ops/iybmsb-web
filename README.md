# iybmsb.com

Static marketing site for IYBMSB. Plain HTML/CSS/JS — no build step.

## Files

- `index.html` — page markup (all placeholder copy in `[brackets]`)
- `styles.css` — theme + layout (brand color in `:root`, currently `--brand: #2b59ff`)
- `main.js` — mobile nav toggle + footer year

## Develop

Just open `index.html` in a browser, or serve locally:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Fill in the placeholders

Search for `[` in `index.html` to find every placeholder:

- Title / meta description
- Full name IYBMSB stands for + tagline
- About paragraphs and stats
- Three service cards
- Contact email, phone, address

The contact form is a stub — wire it to a form service (Formspree, Netlify Forms) or a backend before launch.

## Deploy

**GitHub Pages:** push to GitHub → Settings → Pages → deploy from branch (`main`, root). If this `web/` folder is the repo root, no extra config needed.

**Netlify / Vercel / Cloudflare Pages:** point at this directory, no build command, publish directory is the folder itself.

Set your custom domain (`iybmsb.com`) in the host's domain settings and add the DNS records they provide.
