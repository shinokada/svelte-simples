<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Metrodelaciudaddemexico';
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
  ><title>Metro de la Ciudad de M&#233;xico</title><path
    d="M3.965 8.704V24H.008V6.864h2.097c1.066 0 1.86.774 1.86 1.84m2.366-1.84c.268.521.521 1.315.521 1.84V24h3.685V8.704a1.784 1.784 0 0 0-1.84-1.84M17.4 24V8.704a1.795 1.795 0 0 0-1.844-1.84h-2.382c.269.521.269 1.315.269 1.84V24M.008 3.953V0h15.549c4.75 0 8.435 3.953 8.435 8.704V24h-3.685V8.704a4.735 4.735 0 0 0-4.75-4.75z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Metrodelaciudaddemexico';
-->
