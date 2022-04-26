# Svelte-simples

Svelte-Simpleioncs moved to [Svelte-Simples](https://www.npmjs.com/package/svelte-simples)

Svelte-simples is monochrome SVG Simple icons for Svelte. You can change the color to your choice.

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

## Limitations

If you want to general icons, try [svelte-heros](https://github.com/package/svelte-heros)