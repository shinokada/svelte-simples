<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Flathub';
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
  ><title>Flathub</title><path
    d="M6.068 0a6 6 0 0 0-6 6 6 6 0 0 0 6 6 6 6 0 0 0 5.998-6 6 6 0 0 0-5.998-6Zm9.15.08a1.656 1.656 0 0 0-1.654 1.656v8.15a1.656 1.656 0 0 0 2.483 1.434l7.058-4.074a1.656 1.656 0 0 0 0-2.869l-1.044-.604-6.014-3.47a1.656 1.656 0 0 0-.828-.223Zm3.575 13.135a.815.815 0 0 0-.816.818v2.453h-2.454a.817.817 0 1 0 0 1.635h2.454v2.453a.817.817 0 1 0 1.635 0v-2.453h2.452a.817.817 0 1 0 0-1.635h-2.453v-2.453a.817.817 0 0 0-.818-.818zM2.865 13.5a2.794 2.794 0 0 0-2.799 2.8v4.9c0 1.55 1.248 2.8 2.8 2.8h4.9c1.55 0 2.8-1.25 2.8-2.8v-4.9c0-1.55-1.25-2.8-2.8-2.8Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Flathub';
-->
