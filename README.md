<p align="center">
    <a href="https://www.iviewui.com">
        <img width="200" src="https://file.iviewui.com/logo.svg">
    </a>
</p>

# 基于 iView 2.14.3 镜像
[![](https://img.shields.io/travis/iview/iview.svg?style=flat-square)](https://travis-ci.org/iview/iview)
[![iView](https://img.shields.io/npm/v/iview.svg?style=flat-square)](https://www.npmjs.org/package/iview)
[![NPM downloads](http://img.shields.io/npm/dm/iview.svg?style=flat-square)](https://npmjs.org/package/iview)
[![NPM downloads](https://img.shields.io/npm/dt/iview.svg?style=flat-square)](https://npmjs.org/package/iview)
![JS gzip size](http://img.badgesize.io/https://unpkg.com/iview/dist/iview.min.js?compression=gzip&label=gzip%20size:%20JS&style=flat-square)
![CSS gzip size](http://img.badgesize.io/https://unpkg.com/iview/dist/styles/iview.css?compression=gzip&label=gzip%20size:%20CSS&style=flat-square)
[![Join the chat at https://gitter.im/iview/iview](https://img.shields.io/badge/chat-on_gitter-30b392.svg?style=flat-square)](https://gitter.im/iview/iview?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

### A high quality UI Toolkit built on Vue.js.

> This branch is for Vue.js 2.x.
>
> The branch for Vue.js 1.x can be found [here](https://github.com/iview/iview/tree/master).

## Docs

### [中文文档 (2.x)](https://jackzhcai.github.io/iview-doc-2.x/)


## Features

- Dozens of useful and beautiful components.
- Friendly API. It's made for people with any skill level.
- Extensive documentation and demos.
- It is quite beautiful.
- Supports both Vue.js 2 and Vue.js 1.

## Install

> Please install Webpack first!

We recommend you create your project through [iView Cli](https://github.com/iview/iview-cli) or [iview-project](https://github.com/iview/iview-project). You can also use [vue-cli](https://github.com/vuejs/vue-cli).

### Install iView

Using npm:
```
npm install iview2.x --save
```

Using a script tag for global use:

```html
<script type="text/javascript" src="iview.min.js"></script>
<link rel="stylesheet" href="dist/styles/iview.css">
```

You can find more info [on the website](https://www.iviewui.com/docs/guide/install-en).

## Usage

```vue
<template>
    <Slider v-model="value" range />
</template>
<script>
    export default {
        data () {
            return {
                value: [20, 50]
            }
        }
    }
</script>
```

Using css via `import`:

```js
import 'iview2.x/dist/styles/iview.css';
```

## Compatibility

- Supports Vue.js 2.x
- Supports Vue.js 1.x - [visit 1.0 docs](http://v1.iviewui.com/)
- Supports SSR
- Supports [Nuxt.js](https://nuxtjs.org/)
- Supports [Electron](http://electron.atom.io/)
- iView does not support IE8 or below since [Vue.js](https://vuejs.org/v2/guide/reactivity.html) uses `Object.defineProperty` to track changes which is not supported by these browsers.


## Ecosystem Links

- [iView](https://github.com/iview/iview)
- [iView-Admin](https://github.com/iview/iview-admin)
- [iView-Doc](https://github.com/iview/iview-doc)
- [iView-Cli](https://github.com/iview/iview-cli)
- [iView-Loader](https://github.com/iview/iview-loader)
- [iView-Area](https://github.com/iview/iview-area)

## License
[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2016-present, iView
