# eyu-news

A simple, responsive sport news website built with HTML and CSS.

## Features

- **Pages:** Home, News, Articles, About, Contact, Login
- **12 sport articles** with categories: Premier League, La Liga, Ethiopia Premier League, Top Players
- **Category filter** on the news page (anchor links)
- **Responsive layout** (mobile-first, tablet and desktop breakpoints)
- **Social links** in footer: Telegram, Instagram, Facebook, TikTok
- **Static login** (demo: user@example.com / password123)

## How to run

Open `index.html` in a browser, or serve the folder locally:

```bash
npx serve
# or
python -m http.server 8000
```

Then visit the URL shown (e.g. http://localhost:3000).

## Structure

- `index.html` – Home with featured news cards
- `news.html` – All news grouped by category
- `article.html` – All 12 articles in one page (use `#article-1` … `#article-12`)
- `about.html`, `contact.html`, `login.html`
- `styles.css` – Shared styles

Images are loaded from Pexels (free to use). An internet connection is required for images to display.
