<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Arkecosystem';
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
  ><title>ARK Ecosystem</title><path
    d="M1.8 0C.806 0 0 .805 0 1.8v20.4c0 .995.805 1.8 1.8 1.8h20.4c.995 0 1.8-.805 1.8-1.8V1.8c0-.995-.805-1.8-1.8-1.8H1.8zm10.223 4.39l9.29 15.098-9.29-9.82-9.351 9.82 9.351-15.097zm0 7.583l1.633 1.691h-3.285l1.652-1.691zM9.31 14.762h5.41l1.496 1.574H7.813l1.496-1.574z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Arkecosystem';
-->
