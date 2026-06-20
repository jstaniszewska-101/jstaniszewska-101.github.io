# Deploy to GitHub Pages

## Files in this folder
```
index.html          ← main page
style.css           ← all styles
photo.jpg           ← ADD: your photo (any name, update index.html)
book-cover.jpg      ← ADD: book cover when ready
CV_Joanna_Staniszewska.pdf  ← ADD: your CV PDF
```

---

## Step 1 — Create GitHub repository

Go to github.com → New repository

Name it exactly: `YOUR_GITHUB_USERNAME.github.io`

Example: `joannas.github.io` (username must match exactly)

Set to **Public**. Do NOT add README or .gitignore.

---

## Step 2 — Upload files

Option A (no terminal needed):
1. Open your new repo on GitHub
2. Click **Add file → Upload files**
3. Drag all files from this folder
4. Commit to `main`

Option B (terminal):
```bash
cd path/to/this/folder
git init
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git add .
git commit -m "Launch personal site"
git push -u origin main
```

---

## Step 3 — Enable Pages

1. Go to repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / **root**
4. Save

Your site will be live at `https://YOUR_USERNAME.github.io` in ~2 minutes.

---

## Before publishing — fill in placeholders

Open `index.html` and replace:

| Placeholder | Replace with |
|---|---|
| `YOUR_LINKEDIN_URL` | `https://linkedin.com/in/your-profile` |
| `YOUR_SUBSTACK_URL` | `https://yourname.substack.com` |
| photo placeholder block | `<img src="photo.jpg" alt="Joanna Staniszewska" class="hero-photo" />` |
| book cover placeholder | `<img src="book-cover.jpg" alt="Book cover" class="book-cover-img" />` |

---

## Custom domain (optional)

If you have a domain (e.g. `joannastaniszewska.com`):
1. Add a `CNAME` file to the repo with just your domain inside: `joannastaniszewska.com`
2. In your domain registrar, add a CNAME record: `www → YOUR_USERNAME.github.io`
3. In GitHub Pages settings, set custom domain and enable HTTPS
