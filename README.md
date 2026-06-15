# RecallIQ Customer Re-Engagement Agent

Static browser-only demo. No Node server or backend API is required.

## Run locally

Open `index.html` directly in your browser, or serve the folder with any static file server:

```bash
npm start
```

## Data storage

All customer and campaign data is stored in `localStorage`:

- `recalliq.customers.v1` — customer records
- `recalliq.campaigns.v3` — launched campaigns

On first visit, sample customers are loaded automatically and campaigns start empty.

## Deploy

Deploy the project folder as a static site on [Netlify](https://www.netlify.com/) or [Vercel](https://vercel.com/). Set the publish directory to this folder root (where `index.html` lives).
