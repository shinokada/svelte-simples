<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Processingfoundation';
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
  ><title>Processing Foundation</title><path
    d="M11.999 0a12 12 0 100 24A12 12 0 0012 0zm1.183 5.255h.048c3.273 0 5.247 1.48 5.247 4.103 0 2.727-1.974 4.536-5.295 4.669v-1.742c1.837-.11 2.801-1.061 2.801-2.744 0-1.498-.957-2.442-2.8-2.516zm-1.773.026l.005 11.896c.779.052 1.583.18 2.26.337l-.269 1.324H6.788v-1.324a14.96 14.96 0 012.26-.337V6.993a14.71 14.71 0 01-2.26-.337V5.33h2.26c.64 0 1.469-.028 2.361-.05z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Processingfoundation';
-->
