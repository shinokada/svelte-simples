<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Daf';
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
  ><title>DAF</title><path
    d="M19.649 12.782h-2.643V8.723H24v1.183h-4.351v.723h4.277v1.147h-4.277zm-7.51-3.039l-1.831 3.05H7.76l2.414-4.07h3.924l2.424 4.07h-5.364l.64-1.06h1.534zM.004 12.785V8.741h4.99c1.62 0 2.773.738 2.773 1.994 0 1.196-.914 2.05-2.82 2.05zm4.008-1.034c.621 0 .985-.53.985-.935 0-.413-.325-.896-.967-.896H2.671v1.831zM0 13.731h23.926v1.546H0Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Daf';
-->
