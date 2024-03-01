<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Scrimba';
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
  ><title>Scrimba</title><path
    d="M24 6.222a2.222 2.222 0 01-2.222 2.222h-8.89a2.222 2.222 0 010-4.444h8.89C23.005 4 24 4.995 24 6.222zm-7.333 9.334h-8.89a2.222 2.222 0 000 4.444h8.89a2.222 2.222 0 000-4.444zm0-5.778H13.11a2.222 2.222 0 000 4.444h3.556a2.222 2.222 0 000-4.444zM2.222 15.556a2.222 2.222 0 100 4.444 2.222 2.222 0 000-4.444z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Scrimba';
-->
