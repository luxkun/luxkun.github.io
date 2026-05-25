# luxkun.github.io

Personal portfolio for Luciano Ferraro, Senior AI Gameplay Engineer at Epic Games.

Plain static site (HTML + CSS, no build step). Served by GitHub Pages directly from the repository root.

## Local preview

Any static server will do, for example:

```
python -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Push to the `main` branch of `luxkun/luxkun.github.io`. GitHub Pages serves it at https://luxkun.github.io automatically.

## Files

- `index.html` - single page, all content
- `styles.css` - styling (auto light/dark via `prefers-color-scheme`)
