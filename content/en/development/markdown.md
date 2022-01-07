---
title: 'Markdown'
description: 'Empower your NuxtJS application with this awesome module.'
position: 4
category: 'Development'
version: 1.4
fullscreen: false
menuTitle: 'Markdown features'
items:
  - Item1
  - Item2
  - Item3
link: https://codesandbox.io/embed/nuxt-content-l164h?hidenavigation=1&theme=dark
---

Introducing my awesome Nuxt module!

## Installation

Add `@nuxtjs/xxx` dependency to your project:

<code-group>
  <code-block label="Yarn" active>

  ```bash
  yarn add @nuxtjs/xxx
  ```

  </code-block>
  <code-block label="NPM">

  ```bash
  npm install @nuxtjs/xxx
  ```

  </code-block>
</code-group>

Then, add `@nuxtjs/xxx` to the `modules` section of `nuxt.config.js`:

```js[nuxt.config.js]
{
  modules: [
    '@nuxtjs/xxx'
  ],
  xxx: {
    // Options
  }
}
```

<alert>

Check out an info alert with a `codeblock` and a [link](/themes/docs)!

</alert>

<list :items="items"></list>

<badge>v1.2+</badge>

<code-group>
  <code-block label="Yarn" active>

  ```bash
  yarn add @nuxt/content-theme-docs
  ```

  </code-block>
  <code-block label="NPM">

  ```bash
  npm install @nuxt/content-theme-docs
  ```

  </code-block>
</code-group>

<code-sandbox :src="link"></code-sandbox>
