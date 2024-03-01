<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Typo3';
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
  ><title>TYPO3</title><path
    d="M18.08 16.539c-.356.105-.64.144-1.012.144-3.048 0-7.524-10.652-7.524-14.197 0-1.305.31-1.74.745-2.114C6.56.808 2.082 2.177.651 3.917c-.31.436-.497 1.12-.497 1.99C.154 11.442 6.06 24 10.228 24c1.928 0 5.178-3.168 7.852-7.46M16.134 0c3.855 0 7.713.622 7.713 2.798 0 4.415-2.8 9.765-4.23 9.765-2.549 0-5.72-7.09-5.72-10.635C13.897.31 14.518 0 16.134 0"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Typo3';
-->
