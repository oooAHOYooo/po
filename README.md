Pecan Portfolio — My Wealth Orchard

A minimalist static personal finance site. Calm, long-term, and nature-themed. I plant financial pecans (investments) slowly and consistently, tending an orchard over years.

Water your money tree weekly: invest, learn, review.

## Tech
- Tailwind CSS via CDN (no build step)
- Pure static HTML pages
- Markdown source notes under `src/content/` (optional reference)
- Deployed on Netlify (publish dir: `src/`)

## Structure
```
src/
  index.html
  pages/
    portfolio.html
    rules.html
    library.html
    market-notes.html
    sandbox.html
    tools.html
    glossary.html
    contact.html
    weekly.html
    about.html
  content/
    philosophy.md
    library-phase1.md
    library-phase2.md
    library-phase3.md
  styles/
    main.css   # optional light custom touches (Tailwind is primary)
```

Open `src/index.html` in a browser to view the site. Netlify reads `netlify.toml` and serves `src/` at the root.

## Notes
- Keep pages semantic and accessible
- No emojis; clean, simple headings
- No fancy JS; simple, clear, readable

## Netlify
`netlify.toml` sets:
```
[build]
  publish = "src"
```

## Content Seed
- Philosophy (hero): Growing Pecans
- TLDR Library (Phase 1 → 3)
- Portfolio Orchard allocations and approach
- Weekly Money Watering Plan
- Algo Sandbox reminder: strong roots first — signals later
