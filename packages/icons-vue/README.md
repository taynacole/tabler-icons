# Tabler Icons for Vue

<p align="center">
  <img src="https://raw.githubusercontent.com/tabler/tabler-icons/master/.github/packages/og-package-vue.png" alt="Tabler Icons" width="838">
</p>

<p align="center">
    Implementation of the Tabler Icons library for Vue 3 applications.
<p>

<p align="center">
  <a href="https://tabler-icons.io/"><strong>Browse all icons at tabler-icons.io &rarr;</strong></a>
</p>

<p align="center">
    <a href="https://github.com/tabler/tabler-icons/releases"><img src="https://img.shields.io/npm/v/@tabler/icons" alt="Latest Release"></a>
    <a href="https://github.com/tabler/tabler-icons/blob/master/LICENSE"><img src="https://img.shields.io/npm/l/@tabler/icons.svg" alt="License"></a>
</p>

## Sponsors

**If you want to support my project and help me grow it, you can [become a sponsor on GitHub](https://github.com/sponsors/codecalm) or just [donate on PayPal](https://paypal.me/codecalm) :)**

<a href="https://github.com/sponsors/codecalm">
  <img src='https://raw.githubusercontent.com/tabler/static/main/sponsors.png'>
</a>

## Installation

```
yarn add @tabler/icons-vue
```

or

```
npm install @tabler/icons-vue
```

or

```
pnpm install @tabler/icons-vue
```

or just [download from Github](https://github.com/tabler/tabler-icons/releases).

## How to use

All icons are Vue components that contain SVG elements. So any icon can be imported and used as a component. It also helps to use threeshaking, so you only import the icons you use.


```vue
<template>
  <IconHome />
</template>

<script>
// Returns Vue component
import { IconHome } from '@tabler/icons-vue';

export default {
  components: { IconHome }
};
</script>
```

You can pass additional props to adjust the icon.

```html
<IconHome color="red" :size="48" stroke-width="1" />
```

### Props

| name          | type     | default      |
| ------------- | -------- | ------------ |
| `size`        | _Number_ | 24           |
| `color`       | _String_ | currentColor |
| `stroke`      | _Number_ | 2            |

## Contributing

For more info on how to contribute please see the [contribution guidelines](https://github.com/tabler/tabler-icons/blob/main/CONTRIBUTING.md).

Caught a mistake or want to contribute to the documentation? [Edit this page on Github](https://github.com/tabler/tabler-icons/blob/main/packages/icons-vue/README.md)

## License

Tabler Icons is licensed under the [MIT License](https://github.com/tabler/tabler-icons/blob/master/LICENSE).

## Sponsor Tabler

<a href="https://github.com/sponsors/codecalm" target="_blank"><img src="https://github.com/tabler/tabler/raw/dev/src/static/sponsor-banner-readme.png?raw=true" alt="Sponsor Tabler" /></a>
