<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Googleoptimize';
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
  ><title>Google Optimize</title><path
    d="M23.661 11.997a3.242 3.242 0 1 1-6.479 0V6.55H11.51a3.293 3.293 0 0 1 0-6.55h8.854a3.291 3.291 0 0 1 3.291 3.259l.006 8.738zm-16.775-.011a3.275 3.275 0 1 0-6.55 0 3.275 3.275 0 0 0 6.55 0zm5.42-3.28H5.442c1.153.647 1.944 1.867 1.944 3.28a3.766 3.766 0 0 1-1.802 3.204h3.672v5.453A3.181 3.181 0 0 0 12.372 24a3.323 3.323 0 0 0 3.291-3.357v-8.695a3.318 3.318 0 0 0-3.357-3.242z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Googleoptimize';
-->
