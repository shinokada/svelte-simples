<h1 align="center">Svelte Simples</h1>

<p align="center">
<a href="https://svelte-simples.codewithshin.com/">Svelte-Simples</a>
</p>

<p align="center">
<a href="https://github.com/sponsors/shinokada" target="_blank"><img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86" height="25"></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps" target="_blank"><img src="https://img.shields.io/badge/PWA-enabled-brightgreen" alt="PWA Shield" height="25">
</a>
<a href="https://www.npmjs.com/package/svelte-simples" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/v/svelte-simples" alt="npm" height="25"></a>
<a href="https://twitter.com/shinokada" rel="nofollow" target="_blank"><img src="https://img.shields.io/badge/created%20by-@shinokada-4BBAAB.svg" alt="Created by Shin Okada" height="25"></a>
<a href="https://opensource.org/licenses/MIT" rel="nofollow" target="_blank"><img src="https://img.shields.io/github/license/shinokada/svelte-simples" alt="License" height="25"></a>
<a href="https://www.npmjs.com/package/svelte-simples" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/dw/svelte-simples.svg" alt="npm" height="25"></a>
</p>

SVG Simple icons for Svelte. You can change the size and color to your choice.


Thank you for considering my open-source package. If you use it in a commercial project, please support me by sponsoring me on GitHub: https://github.com/sponsors/shinokada. Your support helps me maintain and improve this package for the benefit of the community.

<p align="center">
<img width="650" src="/static/images/simples-650-1050-optimized.png" />
</p>

## Installation

```sh
npm i -D svelte-simples
```

## Usage

```html
<script>
  import { Facebook } from 'svelte-simples'
</script>

<Facebook />
```


## Faster compiling

If you only need to use a couple of icons from this library in your Svelte app, importing it directly. This can help optimize compilation speed. 
By importing only what you need, you can reduce the amount of code that needs to be processed, which can improve overall performance.


```html
<script>
  import Facebook from 'svelte-simples/Facebook.svelte';
</script>

<Facebook />
```

If you are TypeScript user, install **typescript version 5.0.0 or above**.

As of March 2023, the `typescript@beta` version is now available:

```sh
pnpm i -D typescript@beta
```

To avoid any complaints from the editor, add `node16` or `nodenext` to `moduleResolution` in your tsconfig.json file.

```json
{
  //...
  "compilerOptions": {
    // ...
    "moduleResolution": "nodenext"
  }
}
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

```html
<Facebook class="h-24 w-24 text-blue-700 mr-4" />
```

Bootstrap examples:

```html
<Facebook class="position-absolute top-0 px-1" />
```

## Unfocusable icon

If you want to make an icon unfocusable, add `tabindex="-1"`.

```html
<Facebook tabindex="-1" />
```

## Passing down other attributes

You can pass other attibutes as well.

```html
<Facebook tabindex="0" />
```

## Using svelte:component

```html
<script>
  import { Facebook } from 'svelte-simples';
</script>

<svelte:component this="{Facebook}" />
```

## Using onMount

```html
<script>
  import { Facebook } from 'svelte-simples';
  import { onMount } from 'svelte';
  const props = {
    size: '50',
    color: '#ff0000'
  };
  onMount(() => {
    const icon = new Facebook({ target: document.body, props });
  });
</script>
```

## Import all

Use `import * as Icon from 'svelte-simples`.

```html
<script>
  import * as Icon from 'svelte-simples';
</script>

<Icon.Facebook />

<h1>Size</h1>
<Icon.Facebook size="30" />

<h1>CSS HEX color</h1>
<Icon.Facebook color="#c61515" size="40" />

<h1>Tailwind CSS</h1>
<Icon.Facebook class="text-blue-500" />
```

## Icon images

[Icon images](/icon-images.md)

## Icon names

[Icon names](/icon-names.md)

## Other icons

- [Svelte-Icon-Sets](https://svelte-svg-icons.vercel.app/)

## Experience lightning-fast browsing and offline access with Our PWA

This website can be downloaded and installed on your device for offline access as a Progressive Web App.

To install a PWA, look for the "Add to Home Screen" option in the browser's menu or settings. On most mobile devices, this option can be found by visiting the website, then selecting the "Options" or "Menu" button in the browser, and looking for the "Add to Home Screen" option. On some desktop browsers, right-click on the page and select "Install".