<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Airbrakedotio';
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
  ><title>Airbrake.io</title><path
    d="M15.815.576 24 23.424h-6.072L10.679.576Zm-6.456 0 1.872 5.929-2.447 7.751c1.038.183 2.09.28 3.144.288.576 0 1.175-.048 1.824-.096l1.151 3.912a28.7 28.7 0 0 1-2.951.169 26.568 26.568 0 0 1-4.32-.361L5.88 23.424H0L8.181.576Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Airbrakedotio';
-->
