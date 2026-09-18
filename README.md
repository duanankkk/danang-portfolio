# Danang Haryanto — Portfolio

Personal site built with [Astro](https://astro.build). Static, no client-side JS framework, three pages: home, about, projects.

## Stack

- **Astro 4** — static site generation, file-based routing
- **Fonts** — [Switzer](https://www.fontshare.com/fonts/switzer) (body) + [Khand](https://www.fontshare.com/fonts/khand) (display/headings), loaded from Fontshare
- **Styling** — plain CSS with custom properties (no framework), palette limited to black / white / red
- **Newsletter** — placeholder form in `src/components/Newsletter.astro`, not yet wired to a provider

## Development

```bash
npm install
npm run dev
```

Site runs at `http://localhost:4321`.

## Build

```bash
npm run build
npm run preview
```

Output goes to `dist/`.

## Deploy

Push to GitHub and connect the repo to [Netlify](https://netlify.com) or [Vercel](https://vercel.com) (both have free tiers and auto-detect Astro). No config needed beyond the default build command (`npm run build`) and output dir (`dist`).

## TODO before launch

- Replace all placeholder copy (home, about, projects)
- Add real project content/links in `src/pages/projects.astro` and `src/pages/index.astro`
- Wire up `src/components/Newsletter.astro` form to an email provider (Buttondown, Mailchimp, ConvertKit, etc.)
- Add a real photo in `src/pages/about.astro` (replace the placeholder box)
- Update social links and email address in `src/components/Footer.astro` and `src/pages/about.astro`
- Set the real `site` URL in `astro.config.mjs`
