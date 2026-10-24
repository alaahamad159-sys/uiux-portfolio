# Alaa Ahmad — UI/UX Portfolio

Astro static portfolio for https://alaahamad.site.

## Develop

```bash
npm install
npm run dev
npm run build
```

## Cloudflare Pages

Build command: `npm run build`. Output directory: `dist`. Connect GitHub repository `alaahamad159-sys/uiux-portfolio` to Cloudflare Pages, then add the custom domain once the build passes.

## Content

Edit `src/data/projects.ts` for case-study copy, replace placeholder artwork with real screenshots, and add verified contact details before publishing.

## CI/CD

Pushes to `main` run the Astro build and, when the `CLOUDFLARE_API_TOKEN` GitHub Actions secret is configured, publish the static `dist/` directory to the existing Cloudflare Pages project `alaahamad-portfolio`.
