<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Checkio';
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
  ><title>CheckiO</title><path
    d="M10.846 8.886L24 2.932v13.82L9.621 21.068 0 14.09l3.35-9.956 7.496 4.751v.001zm-4.582 2.067l3.923-1.768-6.065-3.85 2.142 5.618zm-5.393 2.44l4.842-2.187-2.179-5.717-2.662 7.904H.871zm22.526 2.54V4.256l-5.96 7.37 5.96 4.307zm-12.865 4.233l12.497-3.758-5.973-4.316-6.524 8.074zM.94 14.029l8.092 5.867-3.106-8.124L.94 14.029zm21.722-9.826c-5.085 2.296-10.163 4.6-15.25 6.895l9.445.284 5.805-7.178v-.001zM9.775 20.143l6.608-8.173-9.844-.29 3.236 8.462v.001z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Checkio';
-->
