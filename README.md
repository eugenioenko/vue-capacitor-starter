# vue-capacitor-starter

This template should help get you started developing with Vue 3 in Vite.

## Instruction on adding capacitor to existing vue project
- install android studio
- install xcode and xcode dev tools
- https://capacitorjs.com/docs/android

TL DR:

```bash
pnpm add capacitor/core # install core as dependency
pnpm add -D @capacitor/cli # install cli as dev dependency
pnpm add -D @capacitor/android # install android build as dev dependency
npx init cap # init capacitor
npx cap add android # add android build
pnpm build # build dist app
npx cap sync android # sync plugins
npx cap open android # to run in emulator
```


## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
pnpm install
```

### Compile and Hot-Reload for Development

```sh
pnpm dev
```

### Type-Check, Compile and Minify for Production

```sh
pnpm build
```
