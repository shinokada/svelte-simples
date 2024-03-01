<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Nano';
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
  ><title>Nano</title><path
    d="M22.2864 6.8576c-.9453 0-1.7135.7665-1.7135 1.7136 0 1.2843-.4275 1.7136-1.7136 1.7136-.9453 0-1.7135.7664-1.7135 1.7135 0 1.2843-.4276 1.7136-1.7136 1.7136-.9453 0-1.7135.7664-1.7135 1.7135 0 .9454.7665 1.7136 1.7135 1.7136.9454 0 1.7136-.7665 1.7136-1.7136 0-1.2843.4275-1.7135 1.7135-1.7135.9454 0 1.7136-.7665 1.7136-1.7136 0-1.2843.4275-1.7135 1.7135-1.7135.9454 0 1.7136-.7666 1.7136-1.7136 0-.9454-.7682-1.7136-1.7136-1.7136zm-13.717.0017c-.9453 0-1.7135.7665-1.7135 1.7136 0 1.2843-.4275 1.7136-1.7135 1.7136-.9454 0-1.7136.7664-1.7136 1.7135 0 .947.77 1.7135 1.7153 1.7135S6.8576 12.9471 6.8576 12c0-1.2843.4293-1.7135 1.7136-1.7135s1.7136.4275 1.7136 1.7135c0 .947.7698 1.7135 1.7152 1.7135.9453 0 1.7135-.7664 1.7135-1.7135 0-.9454-.7664-1.7135-1.7169-1.7135-1.2843 0-1.7135-.4276-1.7135-1.7136 0-.9453-.7683-1.7136-1.7136-1.7136zm-6.8559 6.856A1.7136 1.7136 0 0 0 0 15.4287a1.7136 1.7136 0 0 0 1.7135 1.7136 1.7136 1.7136 0 0 0 1.7136-1.7136 1.7136 1.7136 0 0 0-1.7135-1.7136Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Nano';
-->
