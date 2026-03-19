# BSSF – Bermuda School Sports Federation

![BSSF Sports Platform](https://img.shields.io/badge/BSSF-Sports%20Platform-e91e8c?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML-Single%20File%20SPA-1e3a8a?style=for-the-badge&logo=html5)
![License](https://img.shields.io/badge/License-MIT-16a34a?style=for-the-badge)

> The official digital platform for the **Bermuda School Sports Federation** — live scores, standings, events, athlete profiles, news, and a full admin dashboard. All in a single HTML file.

---

## Features

### Public Site
- **Home Page** — Live score ticker, upcoming events, weekly winner spotlight, standings preview, blog preview, sports overview
- **Events & Fixtures** — Filterable by sport and status (scheduled, live, completed)
- **League Standings** — Full standings tables for Football, Basketball, Cricket, Track, Swimming
- **Teams & Schools** — All participating school teams with profiles
- **Photo Gallery** — Filterable gallery with lightbox viewer
- **News & Blog** — Full blog with categories, tags, search, featured posts, pagination, and social sharing

### Advanced Blog System
- Featured post hero display
- Category and tag filtering
- Full-text search
- Sidebar with categories, tags, recent posts, and newsletter signup
- Rich blog post detail pages with related articles
- Social sharing (Facebook, Twitter, WhatsApp)
- Reading time estimation
- View counter

### Admin Panel (`/#/admin`)
- **Dashboard** — Stats overview and recent activity
- **Blog Manager** — Create/edit/delete posts with Quill rich text editor; manage categories and tags
- **Events Manager** — Schedule and manage sports events
- **Results Manager** — Record and verify match results
- **Standings Manager** — View and manage league tables
- **Teams Manager** — Manage school teams
- **Players Manager** — Manage athlete profiles
- **Weekly Winners** — Feature athlete achievements
- **Gallery Manager** — Manage photo gallery
- **Settings & Help** — Site configuration and documentation

---

## Theme

Sports-inspired design using a **Pink · Blue · Green** color palette:

| Color | Hex | Usage |
|-------|-----|-------|
| Pink | `#e91e8c` | Primary actions, highlights, badges |
| Blue | `#1e3a8a` / `#2563eb` | Navigation, headers, secondary actions |
| Green | `#16a34a` | Success states, wins, positive indicators |

---

## Getting Started

This is a **zero-dependency single-file SPA**. No build tools required.

```bash
# Clone the repo
git clone https://github.com/ejohnsonbda/bssf.git
cd bssf

# Open in browser
open index.html
# or serve locally
python3 -m http.server 8080
```

Then visit `http://localhost:8080`

---

## Admin Access

Navigate to `/#/admin` or click the **Admin** button in the navigation.

| Username | Password |
|----------|----------|
| admin | safehands |
| admin2 | A7B9C2D4 |
| admin3 | X5Y8Z1W3 |
| admin4 | M9N4P6Q2 |

> **Note:** Change these credentials in production.

---

## Data Storage

All data is stored in **localStorage** (browser-based). The app seeds itself with sample data on first load including:
- 6 teams across 5 sports
- 7 events (scheduled, live, completed)
- Full standings for Football, Basketball, Cricket, Track, Swimming
- 5 players with stats
- 2 weekly winners
- 6 published blog posts with categories and tags
- 9 gallery photos

---

## Deployment

### GitHub Pages
1. Go to repo **Settings → Pages**
2. Source: `main` branch, root folder
3. Save — live at `https://ejohnsonbda.github.io/bssf/`

### Netlify / Vercel
Drag and drop the `index.html` file — instant deployment.

---

## Project Structure

```
bssf/
├── index.html          # Complete single-file SPA
├── README.md           # This file
└── assets/             # Static assets (optional)
```

---

## Technology Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Vanilla HTML5, CSS3, JavaScript (ES6+) |
| Styling | Custom CSS with CSS Variables |
| Typography | Google Fonts (Inter + Oswald) |
| Icons | Font Awesome 6 |
| Rich Text | Quill.js 1.3.7 |
| Data | localStorage (client-side) |
| Routing | Hash-based (`#/page`) |

---

## Contact

- **Admin:** admin@bermudasporthub.com
- **Sports Manager:** sports@bermudasporthub.com
- **Content Manager:** content@bermudasporthub.com

---

*Built for the Bermuda School Sports Federation · 2025*
