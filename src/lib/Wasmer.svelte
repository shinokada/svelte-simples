<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Wasmer';
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
  ><title>Wasmer</title><path
    d="M18.111 3.537c-.011.822-.5 1.208-1.111.86-.611-.353-1.106-1.307-1.111-2.146L12 0v4.651l5.561 3.222.55.32v7.763L22 18.206V5.794l-3.889-2.256Zm-5 3.034c-.011.822-.5 1.208-1.111.86-.611-.352-1.106-1.307-1.111-2.145l-3.89-2.252V7.41l5.562 3.222.55.32v8.038L17 21.241V8.828L13.11 6.57Zm-5 2.759c-.011.822-.5 1.208-1.111.86-.611-.353-1.106-1.307-1.111-2.146L2 5.794v12.413L12 24V11.586L8.111 9.33Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Wasmer';
-->
