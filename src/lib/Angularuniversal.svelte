<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Angularuniversal';
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
  ><title>Angular Universal</title><path
    d="M15.6 11.28v1.44a.48.48 0 0 1-.48.48H8.88a.48.48 0 0 1-.48-.48v-1.44a.48.48 0 0 1 .48-.48h6.24a.48.48 0 0 1 .48.48zM12 15.6a1.2 1.2 0 1 0 0 2.4 1.2 1.2 0 0 0 0-2.4zm3.12-8.4H8.88a.48.48 0 0 0-.48.48v1.44c0 .265.215.48.48.48h6.24a.48.48 0 0 0 .48-.48V7.68a.48.48 0 0 0-.48-.48zm8.04-3.204l-1.716 14.736L11.976 24 2.52 18.732.84 3.996 11.976 0 23.16 3.996zM16.8 6.24a1.44 1.44 0 0 0-1.44-1.44H8.64A1.44 1.44 0 0 0 7.2 6.24v11.52c0 .795.645 1.44 1.44 1.44h6.72a1.44 1.44 0 0 0 1.44-1.44V6.24z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Angularuniversal';
-->
