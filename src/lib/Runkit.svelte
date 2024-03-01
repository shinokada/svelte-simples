<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Runkit';
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
  ><title>RunKit</title><path
    d="M23.97 14.797a3 3 0 01-1.47 3.02l-9 5.2a3 3 0 01-3 0l-9-5.2a3 3 0 01-1.47-3.02l1.32-7.2a3 3 0 01.98-1.82 2.96 2.96 0 01.49-.35l7.55-4.37a3.01 3.01 0 013.28.02l7.53 4.35c.1.05.19.1.28.17a3 3 0 011.19 2zm-9.54-10.77l-7.72 1.59c-.43.08-.51.64-.14.86l5.6 3.23c.23.13.5.07.63-.19l1.58-3.6.53-1.22c.16-.35-.11-.75-.5-.67z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Runkit';
-->
