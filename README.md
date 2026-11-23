# Nanasantoko portfolio

A static Astro portfolio for Nanasantoko. The site includes an introduction, about section, five selected public projects, and a link to the known GitHub profile. Project descriptions are based on their repository READMEs. No contact details have been invented.

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

Push changes to `development` to review them at `https://development.nanasantoko-portfolio.pages.dev/`. Publish the reviewed version to `main` when ready; Cloudflare then updates `https://nanasantoko.dev/`. Git history keeps previous versions available if a change needs to be reverted.

## Personalize

- Edit the text and sections in `src/pages/index.astro`.
- Edit the project entries in `src/pages/index.astro` as the projects evolve.
- Add a verified email or other contact link when available.
- Adjust styles in `src/styles/global.css`.
