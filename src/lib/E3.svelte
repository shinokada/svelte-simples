<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'E3';
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
  ><title>E3</title><path
    d="M11.0676 16.5185H4.7723v-2.6738h6.2615v-3.757H4.7723v-2.64h6.2615V3.691H0v16.6184h14.1476c0-.0339-2.7754-.7108-3.08-3.7908zm10.12-6.3969c1.8954 1.2862 2.8769 2.5385 2.8092 5.1108-.0677 2.6738-2.7754 5.043-5.72 5.043-2.0984 0-4.7723-.9477-5.7876-3.7569l3.4861-1.5569c.4738.88 1.1508 1.557 2.2 1.557 1.1507 0 1.9969-.88 2.0984-1.997.0339-.2708-.1353-2.2338-2.0984-2.3015l-2.2-.237 2.8092-4.5353h-6.3292v-3.757h11.5415z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'E3';
-->
