# Sarcastic Kitchen – Food Blog Landing Page (Adsterra Ready)

A clean, static HTML/CSS landing page inspired by [sarcasticcooking.com](https://www.sarcasticcooking.com/).  
Designed for easy monetization with **Adsterra** and free hosting on **GitHub Pages**.

## Features

- Responsive food-blog layout (header + logo, navigation, large post cards, sticky sidebar)
- Multiple ready-made ad slots:
  - Top 728×90 banner
  - Mid-content Native / 300×250
  - Sidebar 300×250 (×2)
- Clear comments showing exactly where to paste Adsterra codes
- No frameworks, no build step – pure HTML + CSS
- Fast & lightweight (great for Core Web Vitals)

## How to Add Adsterra Ads

1. Log in to your [Adsterra](https://adsterra.com) publisher account.
2. Go to **Websites → Add Website** (or select existing) → **Create Ad Unit**.
3. Recommended formats for this layout:
   - **Popunder** → highest CPM, paste before `</head>`
   - **Social Bar** → paste before `</body>`
   - **Banner 728×90** → top of page
   - **Banner 300×250** (Medium Rectangle) → sidebar + mid-content
   - **Native Banner** → mid-content (blends with posts)

4. Open `index.html` and replace the placeholder comments/divs with your actual ad codes.

**Important Adsterra tips:**
- Never put more than 3–4 banner units on one page.
- Popunder + Social Bar usually give the best revenue.
- Test different placements and check eCPM in the dashboard after a few days.

## Deploy to GitHub Pages (Free)

1. Create a new repository on GitHub (e.g. `sarcastic-kitchen` or `yourusername.github.io`).
2. Upload the contents of this folder (`index.html` + this README).
3. Go to **Settings → Pages**.
4. Under **Source** choose **Deploy from a branch** → `main` / `root`.
5. Wait 1–2 minutes. Your site will be live at:
   - `https://yourusername.github.io/repo-name/`  
   or  
   - `https://yourusername.github.io/` (if you named the repo `yourusername.github.io`)

### Custom Domain (optional)
Add a `CNAME` file with your domain and update DNS as shown in GitHub Pages docs.

## Customization

- Change the logo text, author name, and sample posts inside `index.html`.
- Replace Unsplash images with your own recipe photos.
- Update colors by searching for `#c45c26` (accent) and `#6a9e3e` (green link).
- Add more posts by copying an `<article class="post-card">` block.

## File Structure

```
sarcastic-cooking-landing/
├── index.html      ← the whole site
└── README.md       ← this file
```

That’s it. One HTML file is all you need.

Happy monetizing!
