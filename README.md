# Svelte-simples

Svelte-simples is monochrome SVG Simple icons for Svelte. You can change the size and color to your choice.

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

## Icon names

[Icon names](https://github.com/shinokada/svelte-simples/blob/main/icon-names.md)

## Other icon families

- [Svelte-heros](https://www.npmjs.com/package/svelte-heros) is a set of Heroicons for Svelte.
- [Svelte-lucide](https://www.npmjs.com/package/svelte-lucide) is a set of Lucide icons for Svelte.
- [Svelte-simples](https://www.npmjs.com/package/svelte-simples) is a set of Simple-icons for Svelte.