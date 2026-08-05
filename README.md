# 💗 A Love Story of Learning

A day-by-day, love-themed website for your AI learning series. Each "love note" is a topic page with a simple real-world example — perfect for linking under your LinkedIn post images.

## Structure
```
ai-journey-site/
├── index.html          # The love-story matrix (home)
├── assets/
│   └── style.css       # Romantic theme (shared by every page)
│   └── day1.png ...    # ← drop your LinkedIn cheat-sheet images here
└── days/
    ├── day1.html       # Note 1 · What is an LLM?
    ├── day2.html       # Note 2 · Tokens
    └── day3.html       # Note 3 · Context Window
```

## 🚀 Publish free on GitHub Pages
1. Create a new repo, e.g. `love-story-of-learning`.
2. Upload **everything inside** `ai-journey-site/` to the repo root.
3. Repo → **Settings → Pages** → Source: `main` branch, `/root`.
4. Your site goes live at:
   `https://<your-username>.github.io/love-story-of-learning/`

## 🔗 Link it from LinkedIn
Under each post image, paste the direct note link, e.g.
`https://<your-username>.github.io/love-story-of-learning/days/day3.html`

## ➕ Add a new day
1. Copy `days/day3.html` → `days/day4.html`, edit the content.
2. In `index.html`, remove `locked` from that day's card and set the link.
3. The progress bar updates itself automatically.

## 🖼️ Swap in your cheat-sheet image
On any day page, find the `img-placeholder` box and replace it with:
```html
<img class="cheat-img" src="../assets/day3.png" alt="Note 3 cheat sheet">
```
