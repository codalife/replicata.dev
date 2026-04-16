# replicata.dev

Marketing landing for Replicata. Astro + Tailwind, deploys static to
Cloudflare Pages.

## Dev

```sh
npm run dev
```

Local server at `http://localhost:4321`.

## Build

```sh
npm run build
```

Static output in `dist/`.

## Deploy (Cloudflare Pages)

- **Build command:** `npm run build`
- **Build output directory:** `dist`
- **Root directory:** (repo root)
- **Env vars:** none required — all state lives on Polar.

## TODO before launch

- [ ] Replace `CHECKOUT_URL` in `src/pages/index.astro` with the real
      Polar checkout link. Generate it in Polar dashboard → product →
      share / checkout link. Switch from sandbox to production org.
- [ ] Add `/terms` and `/privacy` pages (currently 404). Generate from
      a template (Termly / Iubenda) then have a lawyer skim.
- [ ] Replace the emoji favicon with a real logo.
- [ ] Drop 3 screenshots or a Loom / YouTube embed into "How it works"
      — most visitors scan images before reading.
- [ ] Wire `hello@` and `support@replicata.dev` via Cloudflare Email
      Routing (free; forwards to your personal inbox).
