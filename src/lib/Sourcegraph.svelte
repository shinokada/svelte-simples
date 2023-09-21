<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Sourcegraph';
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
  ><title>Sourcegraph</title><path
    d="M17.897 3.84a2.38 2.38 0 1 1 3.09 3.623l-3.525 3.006-2.59-.919-.967-.342-1.625-.576 1.312-1.12.78-.665 3.525-3.007zm-8.27 13.313.78-.665 1.312-1.12-1.624-.575-.967-.344-2.59-.918-3.525 3.007a2.38 2.38 0 1 0 3.09 3.622l3.525-3.007zM8.724 7.37l2.592.92 2.09-1.784-.84-4.556a2.38 2.38 0 1 0-4.683.865l.841 4.555zm6.554 9.262-2.592-.92-2.091 1.784.842 4.557a2.38 2.38 0 0 0 4.682-.866l-.841-4.555zm8.186-.564a2.38 2.38 0 0 0-1.449-3.04l-4.365-1.55-.967-.342-1.625-.576-.966-.343-2.59-.92-.967-.342-1.624-.576-.967-.343-4.366-1.55a2.38 2.38 0 1 0-1.591 4.488l4.366 1.55.966.342 1.625.576.965.343 2.591.92.967.342 1.624.577.966.342 4.367 1.55a2.38 2.38 0 0 0 3.04-1.447"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Sourcegraph';
-->
