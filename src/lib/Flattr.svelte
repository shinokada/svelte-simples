<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Flattr';
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
  ><title>Flattr</title><path
    d="M1.906 12C1.906 6.432 6.432 1.906 12 1.906c.048 0 4.003 0 5.455.002L14.53 4.834l1.344 1.344L21.903 0H12C5.373 0 0 5.373 0 12v9.331l1.91-1.759v-.096c-.002-.244-.004-7.404-.004-7.476zM24 2.668l-1.91 1.76v.096L22.093 12c0 5.568-4.528 10.094-10.093 10.094-.048 0-4.003 0-5.455-.002l2.925-2.926-1.344-1.344L2.097 24H12c6.627 0 12-5.373 12-12V2.668z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Flattr';
-->
