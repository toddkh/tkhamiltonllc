# TK Hamilton LLC

Personal site for Todd Hamilton — Technology Strategy & WordPress Specialist.

Built with [Astro](https://astro.build). Deployed on [Cloudflare Pages](https://pages.cloudflare.com).

## Develop

```sh
npm install
npm run dev
```

## Build

```sh
npm run build
npm run preview
```

Requires Node.js 22+.

## Deploy (Cloudflare Pages)

This is a static Astro site. No Cloudflare adapter is required.

1. Push this repo to GitHub.
2. In the [Cloudflare dashboard](https://dash.cloudflare.com) → **Workers & Pages** → **Create** → **Pages** → **Import an existing Git repository**.
3. Select this repo and use:

| Setting | Value |
| --- | --- |
| Framework preset | Astro |
| Production branch | `main` |
| Build command | `npm run build` |
| Build output directory | `dist` |
| Environment variable | `NODE_VERSION` = `22` |

Every push to `main` deploys production. Pull requests get preview URLs automatically.

Optional: attach a custom domain under the Pages project → **Custom domains**.
