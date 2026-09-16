# Astro Blog Playground

A small, hands-on blog built with [Astro](https://astro.build/). This project is a space for experimenting with pages, layouts, components, content collections, and blog styling without the overhead of a larger application.

The playground currently includes:

- A home page with links to the blog and about page
- A blog index with individual post routes
- Markdown and MDX posts with typed frontmatter
- Reusable page, header, footer, and post layout components
- Local fonts and image assets
- RSS feed and sitemap integrations

## Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
├── public/                 # Static files served as-is
├── src/
│   ├── assets/             # Images and local fonts
│   ├── components/         # Shared Astro components
│   ├── content/blog/       # Markdown and MDX posts
│   ├── layouts/            # Reusable page layouts
│   ├── pages/              # Routes, including the RSS feed
│   └── styles/             # Global styles
├── astro.config.mjs        # Astro and integration setup
├── package.json
└── tsconfig.json
```

## Run Locally

Use Node.js `22.12.0` or newer, then run:

```sh
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) to view the blog. The development server reloads as you edit pages, components, styles, or content.

## Common Commands

Run these commands from the project root:

| Command | Purpose |
| :-- | :-- |
| `npm run dev` | Start the local development server |
| `npm run build` | Build the production site in `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run astro -- check` | Check the project for Astro errors |

## Where to Experiment

- Add or edit posts in `src/content/blog/`.
- Update the site title and description in `src/consts.ts`.
- Adjust navigation in `src/components/Header.astro`.
- Change the global visual style in `src/styles/global.css`.
- Customize post structure in `src/layouts/BlogPost.astro`.

See the [Astro documentation](https://docs.astro.build/) for guides on routing, content collections, integrations, and deployment.

