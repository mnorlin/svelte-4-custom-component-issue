This is a minimal implementation of a custom element (aka web component), to compare the js output size between svelte 3 and svelte 4.

| commit                                                                                                              | description   | command                   | output                                       |
| ------------------------------------------------------------------------------------------------------------------- | ------------- | ------------------------- | -------------------------------------------- |
| [318d240](https://github.com/mnorlin/svelte-4-custom-element-issue/commit/318d2404d7ebb61d8e32bd2002643c1c906a4eb5) | Svelte 4      | `npm ci && npm run build` | `index-de4a81a9.js  7.74 kB │ gzip: 3.09 kB` |
| [22e7f08](https://github.com/mnorlin/svelte-4-custom-element-issue/commit/22e7f08d8addc6d0649d1c89a3e5d1dde5c25b3c) | Svelte 3      | `npm ci && npm run build` | `index-b2272fb8.js  4.58 kB │ gzip: 2.08 kB` |
| 3322ade                                                                                                             | clean install |                           |                                              |
