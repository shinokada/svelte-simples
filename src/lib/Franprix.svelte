<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Franprix';
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
  ><title>Franprix</title><path
    d="M12 6.305c3.691 0 6.323-3.071 6.13-6.286-2.124-.17-5.069.791-6.13 3.79C10.939.81 7.993-.15 5.87.02 5.677 3.234 8.309 6.305 12 6.305m11.002 6.962c-.139-3.413-2.821-6.362-6.55-6.362-1.69 0-3.236.635-4.452 1.744-1.217-1.11-2.763-1.744-4.452-1.744-3.729 0-6.412 2.949-6.55 6.362C.758 19.19 5.913 24 12 24c6.087 0 11.242-4.81 11.002-10.733"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Franprix';
-->
