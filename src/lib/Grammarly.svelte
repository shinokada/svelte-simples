<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Grammarly';
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
  ><title>Grammarly</title><path
    d="M24 12c0 6.627-5.373 12-12 12S0 18.627 0 12C0 5.372 5.373 0 12 0c6.628 0 12 5.372 12 12m-9.633 1.626a.81.815 0 00-.799.965c.071.393.44.662.84.662h1.257l.729-.102c-1.166 1.71-3.19 2.498-5.405 2.15-1.802-.282-3.35-1.502-4.003-3.205-1.483-3.865 1.34-7.556 5.02-7.556 1.916 0 3.598 1.122 4.562 2.478.277.39.763.504 1.133.248a.795.8 0 00.236-1.069h.006a7.04 7.04 0 00-6.425-3.233c-3.508.236-6.347 3.107-6.55 6.617-.233 4.086 3.007 7.421 7.037 7.421a6.976 6.976 0 005.304-2.413l-.153.855v.773c0 .4.269.77.662.84a.814.814 0 00.964-.8v-4.63h-4.415"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Grammarly';
-->
