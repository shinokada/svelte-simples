<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Unraid';
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
  ><title>Unraid</title><path
    d="M11.406 8.528h1.17v6.926h-1.17zM1.17 15.454H0V8.528h1.17zm4.534.828h1.17v2.645h-1.17zm-2.86-2.969h1.169v4.282h-1.17zm5.703 0h1.17v4.282h-1.17zM22.83 8.528H24v6.926h-1.17zm-4.534-.81h-1.17V5.073h1.17zm2.86 2.95h-1.169V6.406h1.17zm-5.72 0h-1.17V6.406h1.17z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Unraid';
-->
