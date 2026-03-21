# Portfolio — ImKirit

Single-page portfolio for Bora Duman aka. ImKirit.

## Stack
- Pure HTML/CSS/JS — no build step, no dependencies
- Fonts via Google Fonts (Syne + Outfit)

## Structure
```
Portfolio/
└── index.html   # Everything: HTML, CSS, JS all inline
```

## Design
- Liquid Glass aesthetic with animated blob background
- 5 switchable color themes (Silver, Night, Ocean, Aurora, Ember)
- Silver accents always fixed; base color animates on theme switch
- Scroll-triggered reveal animations (IntersectionObserver)
- Alternating left/right project cards that slide in on scroll

## Hosting
- Target: portfolio.kirit.xyz/imkirit
- Server: root@46.224.104.156
- Web root: /var/www/portfolio/imkirit/
- Served via nginx

## Editing
Just edit `index.html` directly — no build process needed.
After changes: commit, push, then on server: `cd /var/www/portfolio/imkirit && git pull`
