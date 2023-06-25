This is a minimal implementation of a custom element (aka web component), to compare the js output size between svelte 3 and svelte 4.

| commit  | description   | command                   | output                                       |
| ------- | ------------- | ------------------------- | -------------------------------------------- |
| 318d240 | Svelte 4      | `npm ci && npm run build` | `index-de4a81a9.js  7.74 kB │ gzip: 3.09 kB` |
| 22e7f08 | Svelte 3      | `npm ci && npm run build` | `index-b2272fb8.js  4.58 kB │ gzip: 2.08 kB` |
| 3322ade | clean install |                           |                                              |
