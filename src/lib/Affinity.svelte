<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Affinity';
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
  ><title>Affinity</title><path
    d="M9.368 1.08h3.778l.318.55h1.082L24 18.004v.001l-2.036 3.47H13.69l.84 1.445h-.365l-.84-1.446H3.057l-.526-.923h-.652L0 17.298l.002-.001 2.41-4.176 2.23-1.288 3.69-6.39-.742-1.285L9.368 1.08zm2.224 5.652L5.066 18.008h6.25l-.723-1.246 6.808.006-5.809-10.036Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Affinity';
-->
