# vite-vue-template

Avoid full-reload during HotReload

## Setup
 * `npm install vite-vue-template -D

 * `quasar.config.js` : header

```js
import VueTemplateSrc from 'vite-vue-template-src'
```

* `quasar.config.js` : vitePlugins

```js
​[VueTemplateSrc()],
```

## Dev / Build

If any change in the code, please build, then push (I know, it's not conventional)...

To build :
```bash
npx tsc
```
