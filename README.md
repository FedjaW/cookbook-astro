# The Cookbook

I present you the best online cookbook in the world. Check it out: <https://fedjaw.github.io/cookbook-astro/about/>

## Astro

### 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── components/
│       └── Blog.astro
│       └── Footer.astro
│       └── Hamburger.astro
│       └── Header.astro
│       └── Navigation.astro
│       └── Social.astro
│       └── Tag.astro
│   └── layouts/
│       └── BaseLayout.astro
│       └── MarkdownPostLayout.astro
│   └── pages/
│       └── posts/
|           └── 0001_lavacake.md
|           └── 0002_creme_brulee.md
│       └── tags/
|           └── [tag].astro
|           └── index.astro
│       └── about.astro
│       └── blog.astro
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

### 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Tutorial

<https://docs.astro.build/en/tutorial/6-islands/1/>