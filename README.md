# zmbot-site

Static landing page for **zm-bot.com**, deployed via Cloudflare Pages.

Decoupled from the trading bot (in `iam3m/ZMBOT`) so site changes never
restart the live bot.

## Files

- `index.html` — landing page
- `logo.svg` / `favicon.svg` / `og.svg` — branding assets

## Deploy

Connected to Cloudflare Pages, auto-deploys on push to `main`.

## Local preview

Any static file server works. Fast path:

```bash
python -m http.server 8080
```

Then open http://localhost:8080.
