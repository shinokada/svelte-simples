<h1 align="center">Svelte-Simples</h1>

<p align="center">
<a href="https://shinokada.github.io/svelte-simples/">Svelte-Simples</a>
</p>

<p align="center">
<a href="https://www.npmjs.com/package/svelte-simples" rel="nofollow"><img src="https://img.shields.io/npm/v/svelte-simples" alt="npm"></a>
<a href="https://twitter.com/shinokada" rel="nofollow"><img src="https://img.shields.io/badge/created%20by-@shinokada-4BBAAB.svg" alt="Created by Shin Okada"></a>
<a href="https://opensource.org/licenses/MIT" rel="nofollow"><img src="https://img.shields.io/github/license/shinokada/svelte-simples" alt="License"></a>
<a href="https://www.npmjs.com/package/svelte-simples" rel="nofollow"><img src="https://img.shields.io/npm/dw/svelte-simples.svg" alt="npm"></a>
</p>

SVG Simple icons for Svelte. You can change the size and color to your choice.

## Installation

```sh
npm i -D svelte-simples
```

## Import

```html
<script>
  import { Facebook } from 'svelte-simples'
</script>

<Facebook />
```

## Props

| Name  | Default |
| ----- | ------- |
| size  | 24      |
| color | #1877F2 |
| class | ''      |

## Size

Use the `size` prop to change the icon size.

```html
<Facebook size="40" />
```

## Color

Use the `color` prop with a HEX color code to change the icon color.

```html
<Facebook color="#ff0000"/>
```

## CSS framworks suport

Use the class prop to change size, colors and add additional css.

Tailwind CSS example:

```
<Facebook class="h-24 w-24 text-blue-700 mr-4" />
```

Bootstrap examples:

<Facebook class="position-absolute top-0 px-1" />

## Icon names

[Icon names](https://github.com/shinokada/svelte-simples/blob/main/icon-names.md)

## Other icons

- [Svelte-Icon-Sets](https://svelte-svg-icons.vercel.app/)