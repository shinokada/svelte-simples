<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Opentf';
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
  ><title>OpenTF</title><path
    d="m8.168 0-.979.668 10.985 7.116-2.163 1.488-9.318-6.03-.881-.536-.014.022v-.031l-1.093-.666v4.842l3.87 2.679v11.874l.426.284 2.209 1.483 1.269.807v-1.78h-.001v-4.076l1.519 1.002v3.769l1.093-.747v-2.3l.919.606 3.284-2.291v-4.821l.002-.002-.002-.002v-.002l-.002.001-1.107-.743 1.109-.774V7.86l.002-.001v-.642l-.382-.247.009-.004L8.168 0Zm3.217 16.113v5.876l-1.716-1.147V9h-.004l.011-.016L5.798 6.3V3.964l10.232 6.622 2.17-1.493v2.177l-.989.691-.008-.005-.012.019-1.199.836-4.466-2.942v3.759h.001v.369l4.502 2.932 2.171-1.494v2.177l-2.208 1.541-4.607-3.04Zm4.624-1.981 1.214-.847 1.1.739-2.311 1.589-3.392-2.209v-1.505l3.389 2.233Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Opentf';
-->
