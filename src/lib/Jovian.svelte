<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Jovian';
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
  ><title>Jovian</title><path
    d="M20.25 1.65C20.25.74 19.51 0 18.6 0H5.4c-.91 0-1.65.74-1.65 1.65v20.7c0 .91.74 1.65 1.65 1.65h13.2c.91 0 1.65-.74 1.65-1.65V1.65zm-5.275 4.341a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3zm.04 9.018a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3zm-6.015 0a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Jovian';
-->
