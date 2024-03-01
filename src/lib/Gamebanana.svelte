<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Gamebanana';
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
  ><title>GameBanana</title><path
    d="M14.249 0v3h1.5V1.5h1.505V3h-1.505V7.5h1.5V4.5h3.002v-1.5h-1.505V0Zm6.002 4.498v1.5h1.5V4.501Zm1.5 1.5v10.503h1.5V5.998Zm0 10.503h-1.5V19.5h1.5zm-1.5 2.998h-1.505v1.5h1.5zm-1.5 1.5h-3.002v1.5h3.001zm-3.002 1.5H6.75V24h9zm-8.999 0V21h-3v1.5zm-3-1.5v-1.497H2.248v1.5zm-1.501-1.497v-2.997H9.75v-1.5H.748v4.497zm7.502-4.497h2.997v-1.5H9.751Zm2.997-1.5h1.5v-1.501h-1.5zm1.5-1.501h1.501V7.506h-1.5z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Gamebanana';
-->
