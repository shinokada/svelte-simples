<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Nzxt';
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
  ><title>NZXT</title><path
    d="M1.763 8.936l2.101 3.04-.002-3.04h1.773v6.128H3.99l-2.218-3.227v3.227H0V8.936zm22.237 0v1.614h-1.612v4.514h-1.883V10.55h-1.611V8.936H24zm-9.598 0l.996 1.573 1.061-1.573h1.947l-1.98 3.034 2.013 3.094h-2.063l-1.005-1.558-.99 1.558h-2.015l1.975-3.038-2.004-3.09h2.065zm-2.652 0L9.327 13.51h2.372v1.554H6.573l2.379-4.584H6.704V8.936h5.046z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Nzxt';
-->
