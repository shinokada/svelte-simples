<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Wwe';
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
  ><title>WWE</title><path
    d="M24 1.047L15.67 18.08l-3.474-8.53-3.474 8.53L.393 1.048l3.228 8.977 3.286 8.5C3.874 19.334 1.332 20.46 0 21.75c.443-.168 3.47-1.24 7.409-1.927l1.21 3.129 1.552-3.518a36.769 36.769 0 0 1 3.96-.204l1.644 3.722 1.4-3.62c2.132.145 3.861.426 4.675.692 0 0 .92-1.962 1.338-2.866a54.838 54.838 0 0 0-5.138-.092l2.722-7.042zm-21.84.026L8.64 13.86l3.568-9.155 3.567 9.155 6.481-12.788-6.433 8.452-3.615-8.22-3.615 8.22zm10.036 13.776l1.115 2.523a42.482 42.482 0 0 0-2.363.306Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Wwe';
-->
