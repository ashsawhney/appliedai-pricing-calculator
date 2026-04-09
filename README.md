# Opus Pricing Calculator

Internal commercial pricing calculator for Opus — covering the full engagement model from Layer 0 through to Value-Added Services.

## Stack

Pure HTML, CSS, and vanilla JavaScript. No build step, no dependencies, no framework. Drop `index.html` anywhere and it works.

## Deployment

This repo is configured for zero-config deployment on [Vercel](https://vercel.com).

1. Push this repo to GitHub
2. Import the repo in Vercel
3. Vercel auto-detects a static site — no settings needed
4. Deploy

Every push to `main` triggers a new deployment automatically.

## Structure

```
opus-pricing-calculator/
├── index.html      # Single-file application (HTML + CSS + JS)
├── README.md
└── vercel.json     # Vercel routing config
```

## Pricing Layers

| Layer | Name | Type | Price |
|-------|------|------|-------|
| L0 | Value Sprint | One-time | $35,000 |
| L1 | Platform Subscription | Annual · 3-year term | $160,000 / yr |
| L2 | Activation & Implementation | One-time | Variable |
| L3 | Decision & Execution | Annual · consumption | $0.75–$4.00 / txn |
| VAS | Value-Added Services | Mixed | Variable |

## Access

Internal use only. Do not share the URL publicly.
