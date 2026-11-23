# Nana Santoko portfolio

A simple, static Astro portfolio starter for Nana Santoko. The site currently includes an introduction, about section, work placeholder, and a link to the known GitHub profile. No projects or contact details have been invented.

## Run locally

Requires Node.js 22.12 or newer and pnpm.

```sh
pnpm install
pnpm dev
```

Build with `pnpm build`. The finished site is written to `dist/`.

## Deploy on Cloudflare Pages

Connect this GitHub repository to a Cloudflare Pages project, then use:

| Setting | Value |
| --- | --- |
| Production branch | `main` |
| Build command | `npm run build` |
| Build output directory | `dist` |

Cloudflare Pages installs dependencies and deploys the `dist/` folder. The `pnpm-lock.yaml` file makes dependency versions reproducible.

## Personalize

- Edit the text and sections in `src/pages/index.astro`.
- Replace the "Projects coming soon" block with real project details and links.
- Add a verified email or other contact link when available.
- Adjust styles in `src/styles/global.css`.
