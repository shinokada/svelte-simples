<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Googlehangouts';
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
  ><title>Google Hangouts</title><path
    d="M12 0C6.2 0 1.5 4.7 1.5 10.5c0 5.5 5 10 10.5 10V24c6.35-3.1 10.5-8.2 10.5-13.5C22.5 4.7 17.8 0 12 0zm-.5 12c0 1.4-.9 2.5-2 2.5V12H7V7.5h4.5V12zm6 0c0 1.4-.9 2.5-2 2.5V12H13V7.5h4.5V12z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Googlehangouts';
-->
