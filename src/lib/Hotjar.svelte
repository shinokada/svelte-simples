<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Hotjar';
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
  ><title>Hotjar</title><path
    d="M21.055 7.814C17.512 1.404 7.118 0 7.118 0s4.798 5.34-1.334 9.567c-3.876 2.666-5.41 6.13-3.75 9.914 1.27 2.9 3.96 4.076 6.86 4.519-.745-1.434-.932-3.505-.381-5.628.055-.212.116-.434.186-.636.813 1.258 2.148 1.946 3.45 1.629 1.783-.424 2.829-2.582 2.342-4.799a5.104 5.104 0 00-.536-1.372c.07.017.14.024.212.047 2.225.635 3.301 3.962 2.403 7.434a9.266 9.266 0 01-1.325 2.946c3.82-1.23 6.36-4.311 7.06-7.056.736-2.856.177-6.185-1.25-8.751z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Hotjar';
-->
