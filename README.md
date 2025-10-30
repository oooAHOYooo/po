Pecan Grove

A quiet corner of the internet where I plant financial seeds, track my pecan harvests (investments), and gather wisdom about markets, money, and compounding.

Slow growth. Deep roots. Long horizons.

## Project Structure

```
src/
  index.html
  styles/
    main.css
  pages/
    journey.html
    research.html
    resources.html
  components/
    header.html
    footer.html
  data/
    pecan-log.json
```

Open `src/index.html` in a browser to view the site. Subpages are in `src/pages/`.

## Design Notes

- Cozy, natural palette: parchment, pecan brown, muted green
- Serif headers, clean sans body
- Semantic HTML, no JavaScript yet

## CLI Log Script (Concept)

Goal: Append investing logs to `src/data/pecan-log.json` from the command line.

Architecture outline (no code yet):
- Accept CLI flags: `--date`, `--ticker`, `--amount`, `--type`, `--notes`
- Parse inputs, validate types and presence
- Read existing `pecan-log.json` (create if missing)
- Append a normalized entry `{ date, ticker, amount, type, notes }`
- Write back with pretty formatting
- Print an inspirational pecan quote on success

Potential enhancements:
- Support `.env` for defaults
- `--interactive` mode to prompt for fields
- `--import` to batch-add from CSV

## Deploying via GitHub Pages (Prep)

- This repo includes meta tags and a favicon placeholder link in each page head
- Option A: Serve from `/` (move `src/*` files to repo root)
- Option B: Serve from `/docs` (move `src/*` into `docs/` and enable Pages on `docs/`)
- Option C: Keep in `src/` and use a build/copy step in CI to publish

Remember: If using project pages (username.github.io/repo), avoid absolute root paths.
