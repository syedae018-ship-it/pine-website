# Pinewood Interiors & Spaces

Website for **Pinewood Interiors & Spaces**, an interior design studio in Bangalore.

A single static page (`index.html`) with no build step. Open it through any web server, or host it on GitHub Pages, Netlify or Vercel.

## Run locally

```bash
python3 -m http.server 8765
```

Then open http://localhost:8765.

## Files

| Path | What it is |
|---|---|
| `index.html` | The whole site: markup, styles and scripts |
| `logo.png` | Pinewood logo (transparent) |
| `brands/` | Logos of the material brands we use |

## Quote form

The "Get a Free Quote" form sends each request by email through [FormSubmit](https://formsubmit.co). The inbox is set by `QUOTE_EMAIL` near the top of the script in `index.html`. It holds FormSubmit's private alias for the business inbox, not the address itself.

The form only sends when the page is served from a web address (localhost or a live domain), not when `index.html` is opened directly as a file.

## Content to keep up to date

- Phone number in the footer (+91 81978 33092)
- Customer reviews, ratings and stats
- Package details and starting prices
