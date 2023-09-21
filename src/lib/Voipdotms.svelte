<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Voipdotms';
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
  ><title>VoIP.ms</title><path
    d="M17.51 2.372c-.946 0-1.877.24-2.71.696a5.721 5.721 0 0 0-2.055 1.92l-5.177 8.047c-.928 1.446-3.076 1.656-3.92.943l4.051 6.343c.258.402.611.731 1.027.96a2.808 2.808 0 0 0 2.706 0 2.85 2.85 0 0 0 1.025-.96L24 2.371ZM0 8.309l2.228 3.521s.89 1.302 2.402 1.302c1.513 0 2.378-1.302 2.378-1.302l2.23-3.52Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Voipdotms';
-->
