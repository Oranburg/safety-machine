# Judgment Proof — Companion Site

Companion website for *Judgment Proof: The Reign of the Safety Machine versus the Recovery of Human Wisdom* by Seth C. Oranburg (forthcoming).

## Oranburg Style

This site uses the shared Oranburg Style system:
- `assets/css/oranburg-style.css` — design tokens, base styles, nav, footer, theme toggle
- `assets/js/theme.js` — dark/light mode toggle with localStorage persistence

These files are copied from [oranburg.github.io](https://github.com/Oranburg/oranburg.github.io) and should be kept in sync.

## Structure

```
safety-machine/
├── assets/
│   ├── css/
│   │   └── oranburg-style.css    # Shared style foundation
│   └── js/
│       └── theme.js              # Theme toggle
├── index.html                    # Home/hero page
└── README.md
```

## Development

Static HTML/CSS/JS. No build tools. Deploy via GitHub Pages.

Dark mode is default. The theme toggle uses sun/moon SVG icons in the nav bar and persists via localStorage.
