# Onelink

Onelink is an experimental link-in-bio tool, where the data lives in the URL. 

---
### Want to build & ship full stack apps with Nuxt 3? Try [Supersaas](https://supersaas.dev?ref=github)


#### The saas starter kit with Auth, Billing, Database, Storage, KV and lot's of other saas recipes.
---

![Screenshot2023-01-30 at 00 40 04@2x](https://user-images.githubusercontent.com/15716057/215350057-5fbf81f5-5f33-4cbe-98ba-0ced8b3c09c8.jpg)

> **Note**
> Since the URL can become very long, it's better to use a link shortener like https://dub.co



Roadmap.
1. Templates - make different templates, the `/1` after the host is basically a template here.
2. Refactor code - a lot of repeated boilerplate code is added here - refactor it properly.

## Setup locally

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.
