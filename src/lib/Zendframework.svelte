<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Zendframework';
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
  ><title>Zend Framework</title><path
    d="M.932 6.242v2.535h5.652L0 17.757h10.219v-2.534h-5.18l6.553-8.98H.932zm13.537.162c-3.178 0-3.178 3.178-3.178 3.178h9.531C24 9.582 24 6.404 24 6.404h-9.531zm-.006 4.067c-3.173 0-3.172 3.172-3.172 3.172l4.762.005c3.178 0 3.177-3.177 3.177-3.177h-4.767zm0 4.049c-3.173 0-3.172 3.183-3.172 3.183l1.584-.006c3.178 0 3.178-3.177 3.178-3.177h-1.59Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Zendframework';
-->
