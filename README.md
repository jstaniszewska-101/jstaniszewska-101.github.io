# joannastaniszewska.github.io

Personal website of **Joanna Staniszewska** — facilitator, systems thinker, author, and independent consultant working with organizations across the EU and USA.

Live at: **[jstaniszewska-101.github.io](https://jstaniszewska-101.github.io)**

---

## Stack

Pure HTML + CSS. No frameworks, no build tools. One page, fast, works everywhere.

- `index.html` — single-page site
- `style.css` — all styles (Cormorant Garamond + Inter, dusty rose palette)
- `CV_Joanna_Staniszewska.pdf` — downloadable CV (Mentor / EN)
- `photo.jpg` — *(add your photo here)*
- `book-cover.jpg` — *(add when book cover is ready)*

---

## Deploy

This repo is set up for **GitHub Pages**.

1. Push changes to `main`
2. Go to **Settings → Pages → Source: Deploy from branch → main / root**
3. Site is live at `https://jstaniszewska-101.github.io` in ~2 min

---

## Before publishing — add your photo

In `index.html`, find the placeholder block:

```html
<div class="hero-photo-placeholder">
  <span>Your photo</span>
</div>
```

Replace with:

```html
<img src="photo.jpg" alt="Joanna Staniszewska" class="hero-photo" />
```

Then add `photo.jpg` to this folder (square or portrait, min 400×400px).

---

## Custom domain (optional)

1. Add a file named `CNAME` containing your domain: `joannastaniszewska.com`
2. In your DNS provider: `CNAME www → jstaniszewska-101.github.io`
3. In GitHub Pages settings → set custom domain → enable HTTPS

---

## Sections

| Section | Content |
|---|---|
| Hero | Photo · Name · Tagline · Badges · CTA |
| About | Bio in Joanna's voice (from bio-short.md) |
| What I do | Facilitation · Consulting · Writing · Education |
| Credentials | Vanderbilt AI · MITx · KU Leuven · 2BElemental · Awards |
| Book | *A Philosophical Guide to Organizations* — Coming Soon |
| Contact | Email · LinkedIn · Substack · CV download |

---

*Built with Claudian · Being in Systems · 2026*
