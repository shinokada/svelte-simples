<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Bbciplayer';
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
  ><title>BBC iPlayer</title><path
    d="M9.983.004a.142.142 0 0 0-.086.067L7.491 4.237a.141.141 0 0 0 .053.193l12.251 7.074a.141.141 0 0 0 .193-.053l2.405-4.166a.141.141 0 0 0-.053-.193L10.09.02a.142.142 0 0 0-.107-.016ZM1.731 4.785a.14.14 0 0 0-.1.042.141.141 0 0 0-.042.1v14.147c0 .039.017.074.043.1a.14.14 0 0 0 .1.04h4.81a.14.14 0 0 0 .14-.14V4.926a.14.14 0 0 0-.14-.14zm18.171 7.697a.141.141 0 0 0-.107.014L7.544 19.57a.142.142 0 0 0-.053.193l2.406 4.166c.02.034.051.057.086.067a.145.145 0 0 0 .107-.016l12.25-7.072a.142.142 0 0 0 .053-.193l-2.405-4.166a.142.142 0 0 0-.086-.067z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Bbciplayer';
-->
