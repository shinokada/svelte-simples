<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Mozilla';
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
  ><title>Mozilla</title><path
    d="M0 0v24h24V0zm10.13 6.706c1.481 0 2.858.706 3.352 2.224.565-1.377 1.73-2.224 3.353-2.224 1.87 0 3.565 1.13 3.565 3.564v4.765h1.412v2.26h-4.341v-5.86c0-1.8-.6-2.47-1.765-2.47-1.412 0-1.976 1.024-1.976 2.435V15h1.376v2.259h-4.341v-5.824c0-1.8-.6-2.47-1.765-2.47-1.412 0-1.976 1.024-1.976 2.435V15H9v2.259H2.647V15h1.377V9.176H2.647V6.918H6.99V8.47c.635-1.095 1.693-1.765 3.14-1.765z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Mozilla';
-->
