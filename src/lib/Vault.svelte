<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Vault';
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
  ><title>Vault</title><path
    d="M0 0l11.955 24L24 0zm13.366 4.827h1.393v1.38h-1.393zm-2.77 5.569H9.22V8.993h1.389zm0-2.087H9.22V6.906h1.389zm0-2.086H9.22V4.819h1.389zm2.087 6.263h-1.377V11.08h1.388zm0-2.09h-1.377V8.993h1.388zm0-2.087h-1.377V6.906h1.388zm0-2.086h-1.377V4.819h1.388zm.683.683h1.393v1.389h-1.393zm0 3.475V8.993h1.389v1.388Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Vault';
-->
