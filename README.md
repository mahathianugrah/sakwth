# 6am Fresh 🌿

**Start Fresh. Stay Fresh.**

A modern community supermarket landing page with dark/day mode, product catalogue, cart, and sign-up modal.

## 🚀 Live Demo

Deployed via GitHub Pages → `https://<your-username>.github.io/6am-fresh/`

## 📁 Project Structure

```
6am-fresh/
├── index.html        # Main site (self-contained, all CSS & JS inline)
└── README.md         # This file
```

## 🛠️ Deploy to GitHub Pages

### Option 1 — GitHub Web UI (easiest)

1. Go to [github.com](https://github.com) and click **"New repository"**
2. Name it `6am-fresh`, set it to **Public**, click **Create repository**
3. Click **"uploading an existing file"** → drag & drop `index.html` and `README.md`
4. Commit the files
5. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
6. Click **Save** — your site will be live in ~1 minute

### Option 2 — Git CLI

```bash
# 1. Clone your new empty repo
git clone https://github.com/<your-username>/6am-fresh.git
cd 6am-fresh

# 2. Copy the files into it
cp /path/to/index.html .
cp /path/to/README.md .

# 3. Push
git add .
git commit -m "🚀 Initial deploy: 6am Fresh landing page"
git push origin main

# 4. Enable Pages in repo Settings → Pages → main / root
```

## ✨ Features

- 🌙 Dark / ☀️ Day mode toggle
- 🛒 Slide-out shopping cart
- 📦 Product catalogue with category filters
- 🔐 Sign-up & login modal
- 📱 Fully responsive (mobile-first)
- 🖱️ Custom cursor with hover effects
- ⚡ Zero dependencies — no build step needed

## 🧰 Tech Stack

- Pure HTML5, CSS3 (CSS variables, grid, flexbox)
- Vanilla JavaScript (no frameworks)
- Google Fonts (Plus Jakarta Sans, Nunito, Playfair Display)
