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

## Experience lightning-fast browsing and offline access with Our PWA

This website can be downloaded and installed on your device for offline access as a Progressive Web App.

To install a PWA, look for the "Add to Home Screen" option in the browser's menu or settings. On most mobile devices, this option can be found by visiting the website, then selecting the "Options" or "Menu" button in the browser, and looking for the "Add to Home Screen" option. On some desktop browsers, right-click on the page and select "Install".