<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Hackernoon';
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
  ><title>Hacker Noon</title><path
    d="M5.701 0v6.223H8.85V4.654h1.576v7.842H12V4.654h1.574v1.569h3.15V0zm11.024 6.223v3.136h1.574V6.223zm1.574 3.136v4.705h1.576v-1.568h1.574v-1.568h-1.574V9.359zm0 4.705h-1.574v3.137h1.574zm-1.574 3.137h-3.15v1.569H8.85V17.2H5.7V24h11.024zm-11.024 0v-3.137H4.125v3.137zm-1.576-3.137V9.36H2.551v4.705zm0-4.705h1.576V6.223H4.125Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Hackernoon';
-->
