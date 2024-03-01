<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Beatsbydre';
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
  ><title>Beats by Dre</title><path
    d="M12.0099 15.5996A3.5995 3.5995 0 1 0 8.4103 12a3.5995 3.5995 0 0 0 3.5996 3.5996zm0-15.5981a11.9985 11.9985 0 0 0-3.5996.552v6.6471A5.9992 5.9992 0 1 1 6.0106 12V1.6033A11.9985 11.9985 0 1 0 12.01.0015z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Beatsbydre';
-->
