<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Castorama';
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
  ><title>Castorama</title><path
    d="M8.91 16.106c-2.129 0-3.659-1.794-3.659-4.266 0-2.148 1.468-4.095 3.488-4.095 2.275 0 3.545 1.857 3.545 1.857l2.939-3.298c-.91-1.062-2.598-2.882-6.503-2.882-4.388 0-8.209 3.489-8.209 8.456 0 4.766 3.475 8.532 8.266 8.532 3.855 0 5.572-2.017 6.54-3.129l-2.831-2.969c0 .001-1.415 1.794-3.576 1.794zM18.283 0v9.988h-2.064a1.92 1.92 0 1 0 0 3.84h2.064V24h5.205V0h-5.205z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Castorama';
-->
