# neon\\BLADE (website)

This is the source code of the website of the game neon\\BLADE (https://neonblade.pages.dev)

# File structure

## /static/ss
Screenshots of the game

## /src/rotes/PageContent.svelte
Contents of the page

## /src/lib/components
### ./ui
shadcn/svelte components

### ./Hero.svelte
The hero section

### ./Footer.svelte
Site footer

---

Everything bellow is the original svelte cli readme

# sv

Everything you need to build a Svelte project, powered by [`sv`](https://github.com/sveltejs/cli).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```sh
# create a new project in the current directory
npx sv create

# create a new project in my-app
npx sv create my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```sh
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```sh
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.
