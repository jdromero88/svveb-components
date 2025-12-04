# svveb-components [![Deploy-Svveb-Components](https://github.com/jdromero88/svveb-components/actions/workflows/deploy-svveb-comp.yml/badge.svg)](https://github.com/jdromero88/svveb-components/actions/workflows/deploy-svveb-comp.yml)
Web Components made with Svelte.
- `node v24.11.1 (npm v11.6.2)`
- `svelte v5.41.0`



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

## Copyright / License
Copyright © 2022 CSIS iDeas Lab under the [License](LICENSE).
