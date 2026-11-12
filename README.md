# Laura Herrero González · Product Coaching website

Static site in `site/` (index.html + assets), served by a Cloudflare Worker with static assets.

- Local preview: `npm install && npm run dev` → http://localhost:8787
- Deploy: push to `main` — Cloudflare Workers Builds runs `npx wrangler deploy`.
