# `@vue-generic` breaks the Vize content mapper's TSX

```sh
npm install
npm run check
```

`src/App.vue` gives `error TS17008: JSX element 'C' has no corresponding closing tag.` in virtual code. Removing the `<!-- @vue-generic -->` comment makes the check pass.
