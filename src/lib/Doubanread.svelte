<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Doubanread';
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
  ><title>Douban Read</title><path
    d="M15.328 5.553c-2.648.906-4.008 4.372-7.101 4.833C4.827 10.833.752 7.205 0 6c0 0 .526.906 1.28 2.105C5.205 14.297 7.772 18.224 12 18.75c5.28.68 8.146-4.535 8.826-6.64.607-1.732 1.733-1.66 2.494-1.433l.68.227s-2.729-7.402-8.688-5.36l.016.008z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Doubanread';
-->
