---
title: 'The components Property'
description: 'Nuxt.js 2.13+ can scan and auto import your components using @nuxt/components module'
menu: components
category: configuration-glossary
position: 5
---

> Nuxt.js 2.13+ can scan and auto import your components.

- Type: `Boolean` or `Object`
- Default: `false`

When set to `true` or using an object, it will include the [nuxt/components](https://github.com/nuxt/components) dependencies and auto import your components (defined in `~/components`) when you use them in your templates.

Be careful when working on large projects with many components. Using `components: true` can increase hot reload times drastically. 
If you start seeing very long hot reloads, set `components: false` and import the components in each file manually instead.

<base-alert type="info">

Please refer to [nuxt/components](https://github.com/nuxt/components) repository for usage and options.

</base-alert>
