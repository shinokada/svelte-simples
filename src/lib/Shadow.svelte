<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Shadow';
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
  ><title>Shadow</title><path
    d="M12 0C5.3727 0 0 5.3727 0 12c0 3.5145 1.511 6.6754 3.9181 8.8702a4.457 4.457 0 01-.1998-1.3238c0-2.4597 1.9938-4.4535 4.4536-4.4535 2.4596 0 4.4535 1.9938 4.4535 4.4535 0 1.9565-1.262 3.6171-3.016 4.2153C10.382 23.9178 11.1815 24 12 24c6.6273 0 12-5.3727 12-12S18.6273 0 12 0Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Shadow';
-->
