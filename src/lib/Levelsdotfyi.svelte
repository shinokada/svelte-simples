<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Levelsdotfyi';
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
  ><title>levels.fyi</title><path
    d="M2.494 18.913h3.52v-3.52c0-.43.35-.78.781-.78h3.52v-3.52c0-.432.35-.783.781-.783h3.52V6.791c0-.432.35-.782.782-.782h3.519V2.49c0-.432.35-.782.782-.782h3.52c.43 0 .781.35.781.782v20.724c0 .432-.35.782-.782.782H2.494a.782.782 0 0 1-.782-.782v-3.52c0-.43.35-.78.782-.78ZM.172 15.928a.587.587 0 0 1 0-.83L15.102.168a.587.587 0 0 1 .83.83l-14.93 14.93c-.23.23-.6.23-.83 0Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Levelsdotfyi';
-->
