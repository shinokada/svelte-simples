<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Babylondotjs';
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
  ><title>Babylon.js</title><path
    d="M22.392 6 19.14 4.123 16.01 5.93l3.253 1.878zM4.737 7.807l10.391-6L12 0 1.608 6Zm4.01 6.07L12 15.758l3.252-1.877L12 12Zm10.515-6.07v8.387L12 20.387l-7.263-4.193V7.806L1.608 6.001v12L12 24l10.392-6V6ZM12 8.245l-3.253 1.878v3.757L12 12l3.252 1.879v-3.757z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Babylondotjs';
-->
