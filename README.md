# Open RTLS at GeoIT Symposium

Short Reveal.js presentation for the GeoIT Symposium on 16 March 2026.

The deck presents an indoor-mapping-first Open RTLS narrative and is built as a static site with [Reveal.js](https://revealjs.com/).

## Local preview

```bash
bunx serve .
```

Then open [http://localhost:3000](http://localhost:3000).

Optional Cloudflare-style preview:

```bash
npx wrangler pages dev .
```

## Project files

- `index.html`: Reveal.js entrypoint
- `slides.md`: slide content
- `open-location-stack.css`: presentation styling
- `assets/`: logos and SVG visuals
