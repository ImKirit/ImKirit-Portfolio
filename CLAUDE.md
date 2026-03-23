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
- EN/DE language toggle (US/DE flag) in nav — all text via data-i18n + translations object, fade animation on switch
- "You want your own Portfolio? Let me know!" banner above contact links
- "& more" section at bottom of projects
- Terminal animation (PowerShell): boot sequence, block-ASCII "IMKIRIT", menu cursor selecting "Projects", then typing commands
- 3D Glass Card Tilt on project visuals (mousemove parallax + glass reflection overlay)

## Hosting
- Primary: https://imkirit.dev/portfolio-imkirit (SSL active)
- Legacy: https://portfolio.kirit.xyz/imkirit (SSL active)
- Server: root@46.224.104.156
- Web root: /var/www/portfolio/
- Served via nginx, certbot auto-renewal
- Git repo: https://github.com/ImKirit/ImKirit-Portfolio.git

## Editing
Just edit `index.html` directly — no build process needed.
After changes: commit, push, then on server: `cd /var/www/portfolio && git pull`

## Commit format
`dd.mm.yy - Description`

## Related
- Portfolio Builder: ../Portfolio-Builder/index.html (interactive builder tool)
- Portfolio Generator Skill: ~/.claude/commands/portfolio-generator.md (invoke with /portfolio-generator)
- Motion Designs: ../Motion-Designs/ (Remotion project with 6 compositions)
