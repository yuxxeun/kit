# kit

This website is built with SvelteKit, is an application framework powered by Svelte — build bigger apps with a smaller footprint.

SvelteKit is a framework for building web applications of all sizes, with a beautiful development experience and flexible filesystem-based routing.

Unlike single-page apps, SvelteKit doesn't compromise on SEO, progressive enhancement or the initial load experience — but unlike traditional server-rendered apps, navigation is instantaneous for that app-like feel.

Basically I don't care with any SEO-related things, I use SvelteKit over Svelte was for flexibility sake on filesystem-based routing.

## Getting started

Ah, here we go again.

1. Clone this repo
2. Run `yarn`
3. Take S2 program
4. Does yarn install still running? If yes, take PhD program
5. If not, run `yarn dev`
   Anyone here still using `npm` over `yarn`?

## Directory Structures

All routes are lives in `src/routes` directory. I use common (read: boring) naming conventions in naming directory and file. So you should be familiar.

## Developing

start a development server:

```bash
yarn dev

# or start the server and open the app in a new browser tab
yarn dev -- --open
```

## Production Environment

This site is should be statically generated so you need to run `yarn build`. Also, this site probably will be deployed to Netflify. Or Zeit Now aka Vercel? Or Docker? Or to my kubernetes clusters? Who knows?

## License

`MIT`. Why not.
