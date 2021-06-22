# sveltekit-boilerplate

Everything you need to build a Svelte project using the following tools and libraries:

- [sveltekit](https://gi)
- [Vite](https://vitejs.dev/)
- [WindiCSS](https://windicss.org/)
- [PWA](https://web.dev/progressive-web-apps/)
- typescript
- eslint
- prettier

## Set-up

If you do not already have `degit` installed, run:

```zsh
 npm install -g degit
```

Then create your new project:

```zsh
npx degit cswkim/sveltekit-boilerplate my-new-app
```

Install the dependencies (we are using `pnpm` for the example but you can of course use `npm` or `yarn` as well):

```zsh
cd my-new-app
pnpm install
```

## Developing

Now that the starter kit is set-up, boot up the dev server:

```zsh
pnpm run dev

# have the app be accessible on your local network
pnpm run dev -- --host 0.0.0.0
```

## Building

Before creating a production version of your app, install an [adapter](https://kit.svelte.dev/docs#adapters) for your target environment. Then:

```zsh
pnpm run build
```

> You can preview the built app with `pnpm run preview`, regardless of whether you installed an adapter. This should _not_ be used to serve your app in production.
