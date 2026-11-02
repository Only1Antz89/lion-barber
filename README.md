# Lions Barbers — Croydon

Marketing website for Lions Barbers at 2 Mint Walk, Croydon.

## Source

Synced from published Sites version 9, source commit `9b57ff4823ea5a50daf24259335accf575125656`.
The static website lives in `dist/`. Booking and live shop links connect to the existing Barber Dresser platform.

## Local preview

```sh
python3 -m http.server 8080 --directory dist
```

## Deployment

Vercel serves `dist/` directly using `vercel.json`; no build step or environment variables are required.
Production deployments follow the `main` branch.
