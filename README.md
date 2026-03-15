# VITH HUB — Mekong Trade Gateway Platform

> Trade Platform + Expo Platform + Market Gateway — Built to Scale into Mekong Trade Platform

## Project Structure

```
/vithhub-site
│
├── index.html                  ← Homepage
│
├── /pages
│   ├── about.html
│   ├── event.html
│   ├── membership.html
│   ├── accelerator.html        ← 90 Day Accelerator Program
│   ├── gateway.html            ← Mekong Trade Gateway
│   ├── floorplan.html
│   └── salesdeck.html
│
├── /assets
│   ├── /css
│   │   └── vith-design.css     ← Global Design System
│   │
│   ├── /js
│   │   └── main.js             ← Global JavaScript
│   │
│   ├── /images                 ← All images go here
│   │   └── (partner logos, hero images, etc.)
│   │
│   └── /fonts                  ← Self-hosted fonts (optional)
│
└── README.md
```

## Design System

### Colors
- `--navy: #0B1F3B` — Primary dark navy
- `--gold: #C9A227` — Primary gold
- `--gold2: #E4BC4A` — Light gold
- `--goldDk: #9B7A10` — Dark gold

### Typography
- **Headings**: Plus Jakarta Sans (700–800)
- **Body**: Inter (400–600)
- **Thai text**: Noto Sans Thai (fallback)

### CSS Import
```html
<link rel="stylesheet" href="/assets/css/vith-design.css">
```

### JS Import (before </body>)
```html
<script src="/assets/js/main.js"></script>
```

## URL Structure
| Path | Page |
|------|------|
| `/` | Homepage |
| `/pages/gateway.html` | Mekong Trade Gateway |
| `/pages/accelerator.html` | 90 Day Accelerator |
| `/pages/event.html` | Expo 2026 |
| `/pages/membership.html` | Membership |
| `/pages/about.html` | About VITH HUB |
| `/pages/floorplan.html` | Floor Plan |
| `/pages/salesdeck.html` | Sales Deck |

## Images
Place all images in `/assets/images/`:
- `hero.jpg` — Homepage hero
- `expo.jpg` — Expo section
- `bigc.jpg` — Big C Vientiane
- `laos-market.jpg` — Market imagery
- Partner logos: `bigc-logo.svg`, `litse-logo.svg`, etc.

## Notes
- All paths use absolute `/assets/...` for compatibility with any hosting setup
- CSS is in a single file: `vith-design.css`
- JS is in a single file: `main.js`
- No inline `<style>` blocks (page-specific styles are kept minimal and scoped)
- Google Fonts loaded via `<link>` in every page `<head>`

---
© 2026 VITH HUB · vithhub.asia
