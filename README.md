# Astro Starter Kit: JG Starter

```sh
yarn && yarn dev // install dependencies && start dev server
```

## Important 
*If you are contributing to this starter kit, ignore this entire message*.  
Remove the remote origin to this repo, check it has been removed (should return empty), and set a new one to your desired remote origin.
```sh
git remote remove origin
git remote -v
git remote add origin <new-repo-url>
```

## Project Structure
### Packages
 - TypeScript
 - sass-embedded (SCSS integration)

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── components/
        │   └── Test.astro
│   └── layouts/
│       └── Layout.astro
│   └── pages/
│       └── index.astro
│   └── styles/
│     └── base/
│     └── components/
│     └── styles.scss
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `yarn`             | Installs dependencies                            |
| `yarn dev`             | Starts local dev server at `localhost:4321`      |
| `yarn build`           | Build your production site to `./dist/`          |
| `yarn preview`         | Preview your build locally, before deploying     |
| `yarn astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `yarn astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
