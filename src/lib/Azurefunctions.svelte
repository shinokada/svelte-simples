<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Azurefunctions';
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
  ><title>Azure Functions</title><path
    d="M10.537.904L6.602 12.04l4.798.037-3.748 11.018v.002L17.996 8.39h-5.022L17.847.903h-3.824zM6.903 4.91a.585.585 0 0 0-.412.17L.155 11.285a.682.682 0 0 0 0 .865l6.448 6.396a.625.625 0 0 0 .824 0 .638.638 0 0 0 0-.865l-5.436-5.53a.641.641 0 0 1 0-.865l5.324-5.344a.574.574 0 0 0 0-.865.586.586 0 0 0-.412-.169zm10.193 0a.585.585 0 0 0-.412.17.572.572 0 0 0 0 .864l5.435 5.343a.64.64 0 0 1 0 .866l-5.548 5.53a.64.64 0 0 0 0 .865.625.625 0 0 0 .824 0l6.45-6.396a.68.68 0 0 0 0-.865l-6.337-6.208a.585.585 0 0 0-.412-.169z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Azurefunctions';
-->
