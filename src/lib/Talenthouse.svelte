<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Talenthouse';
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
  ><title>Talenthouse</title><path
    d="M22.373 7.42V0H1.627v7.42h6.66V24h7.428V7.42h6.66zM12.31 0h-.623zm-.004 3.41V.618h8.865L17.652 3.41Zm-5.948 0L2.83.618h8.857V3.41H6.358zm-.608.308-3.503 2.76V.949ZM2.837 6.802l3.52-2.781h4.894L8.46 6.8H2.837Zm6.068.438 2.78-2.782v14.781l-1.602 2.046-1.183 1.51Zm.326 16.142.555-.706 2.216-2.825 2.77 3.535zm3.078-18.924 2.786 2.782v15.556l-2.786-3.556zM15.55 6.8l-2.8-2.78h4.904l3.519 2.78h-5.623Zm6.206-.322L18.25 3.71 21.744.963l.02-.015Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Talenthouse';
-->
