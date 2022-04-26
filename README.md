# Svelte-simpleicons

Svelte-simpleicons is a monochrome SVG icons. You can change the color to your choice.

## Requirement

TailwindCSS

## Installation

```sh
npm i -D @codewithshin/svelte-simpleicons
```

## Import

```html
<script>
  import { FacebookIcon } from 'svelte-simple-icons'
</script>

<FacebookIcon className="h-8 w-8 w-full" fill="#4287f5" />
```

## Props

| Name      | Default   |
| --------- | --------- |
| className | h-6 w-6   |
| viewBox   | 0 0 24 24 |
| fill      | #000000   |

## Limitations

If you want to general icons, try [svelte-heroicons](https://github.com/shinokada/svelte-heroicons)