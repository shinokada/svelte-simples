<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Rxdb';
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
  ><title>RxDB</title><path
    d="M11.096 3.452h1.15v-1.15h1.151v1.15h6.411v4.932H4.192V1.15h1.15V2.3h1.151V0h1.15v1.15h1.152v2.302h1.15V1.151h1.151v2.301zM4.192 14.466h15.616V9.534H4.192v4.932zm15.616 1.15H4.192v4.932h6.41v1.15h1.151v-1.15h1.151v2.301h1.15v-2.301h1.152v2.301h1.15V24h1.151v-2.301h1.15v1.15h1.151v-7.233z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Rxdb';
-->
