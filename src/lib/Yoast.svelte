<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Yoast';
</script>

<svg
  viewBox="0 0 24 24"
  width={size}
  height={size}
  fill={color}
  {...$$restProps}
  {role}
  aria-label={ariaLabel}
  on:click
  on:keydown
  on:keyup
  on:focus
  on:blur
  on:mouseenter
  on:mouseleave
  on:mouseover
  on:mouseout
  xmlns="http://www.w3.org/2000/svg"
  ><title>Yoast</title><path
    d="M15.864 0L14.55 3.652H5.422A3.592 3.592 0 0 0 1.84 7.233v9.529a3.592 3.592 0 0 0 3.582 3.581h1.495a4.9 4.9 0 0 1-.18.029l-.34.047V24h.391c2.76 0 4.442-1.385 5.706-3.657h9.666V7.233a3.593 3.593 0 0 0-3.253-3.565L20.275 0zm.556.778h2.738l-6.055 16.22c-1.55 4.335-3.186 6.064-5.924 6.21v-2.12c1.767-.354 2.418-1.461 2.785-2.408a3.902 3.902 0 0 0 0-2.828L6.43 6.772h2.488l2.512 7.86z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Yoast';
-->
