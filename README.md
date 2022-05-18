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
- [Svelte-Ionicons](https://www.npmjs.com/package/svelte-ionicons)
- [Svelte-Awesome-Icons](https://www.npmjs.com/package/svelte-awesome-icons)
- [Svelte-heros](https://github.com/shinokada/svelte-heros)
- [Svelte-lucide](https://github.com/shinokada/svelte-lucide)
- [Svelte-flags](https://www.npmjs.com/package/svelte-flags)
- [Svlete-simples](https://github.com/shinokada/svelte-simples)
- [Svelte-feathers](https://github.com/shinokada/svelte-feathers)