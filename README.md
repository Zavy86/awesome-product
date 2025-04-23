# Build a Static Website with Astro and GitHub Actions & Pages
Have you created your **own digital product** and want to build a website to promote it online?  
Would you like to create a **simple static landing page**, perhaps even with a **well-crafted documentation** section?

Then **Astro** and **GitHub** are the ideal solution for you!

## Complete Tutorial on YouTube
[![astro-github-actions-pages](https://img.youtube.com/vi/4LblKbNUu0E/mqdefault.jpg)](https://youtu.be/4LblKbNUu0E "Crea un SITO WEB statico con ASTRO e GitHub ACTIONS ospitato GRATUITAMENTE su GitHub PAGES!")  
[https://youtu.be/4LblKbNUu0E](https://youtu.be/4LblKbNUu0E)

## 🚀 Project Structure

Inside of your Astro + Starlight project, you'll see the following folders and files:

```
.
├── public/
├── src/
│   ├── assets/
│   ├── content/
│   │   ├── docs/
│   └── content.config.ts
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

Starlight looks for `.md` or `.mdx` files in the `src/content/docs/` directory. Each file is exposed as a route based on its file name.

Images can be added to `src/assets/` and embedded in Markdown with a relative link.

Static assets, like favicons, can be placed in the `public/` directory.

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

## 👀 Want to learn more?

Check out [Starlight’s docs](https://starlight.astro.build/), read [the Astro documentation](https://docs.astro.build), or jump into the [Astro Discord server](https://astro.build/chat).
