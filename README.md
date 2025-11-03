# vite-vue-template

Avoid full-reload during HotReload

## Setup
 * `npm install git+https://github.com/ICOWSOFT/vite-vue-template-html.git -D`

 * `quasar.config.js` : header

```js
import VueTemplateSrc from 'vite-vue-template-html'
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

# Upgrade

```
npx npm-check-updates -u
npm install
git add .
git commit -m"Upgrade lib"
git push
```

## Credits

 * "author": "m310851010",
 * "homepage": "https://github.com/m310851010/vite-vue-template-src#readme",