# Devmotion Landing Page

The official repository for the Devmotion landing page.

> Built with [Astro🚀](https://astro.build)

![Paige preview](https://raw.githubusercontent.com/Dev-Motion/.github/main/assets/devmotion-preview.png)

## 🚀 Project Structure

Inside repository, you'll see the following folders and files:

```text
/
├───.vscode
├───public
└───src
    ├───assets
    │   └───images
    ├───components
    ├───icons
    ├───layouts
    ├───pages
    └───utils
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

The `src/components/` directory for our components. Astro uses the [Snowpack](https://www.snowpack.dev/) module bundler, which means that each component is its own module. This allows us to use the same component in multiple pages without worrying about collisions.

The `src/layouts/` directory contains the layout components for our site. Layouts are special components that wrap other components, and are used to create a consistent layout across multiple pages.

The `src/assets/` directory is where we keep our static assets like images.

The `src/utils/` directory is where we keep our utility functions. These are functions that are used across multiple components, like a function that lets you create class names conditionally while merging of tailwind classes when needed.

The `src/icons/` directory is where we keep our SVG icons. These icons are used across multiple components and are automatically optimized by the `astro-icon` library.

Any static assets that doesn't need optimization, like favicon, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Contributing

If you want to contribute to this project, please read the [CONTRIBUTING.md](#) file.
