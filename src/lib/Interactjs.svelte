<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Interactjs';
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
  ><title>InteractJS</title><path
    d="M12.382.01C12.255.006 12.128 0 12 0A11.999 11.999 0 0 0 1.804 18.327l9.911-17.17zm7.097 19.686L11.201 5.121 2.788 19.689l.007.007h16.684zm.184 1.538H4.337a11.998 11.998 0 0 0 15.326 0zm2.917-3.568A11.999 11.999 0 0 0 12.382.01l.667 1.148zM12.383.009l-.001.001h.001V.009z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Interactjs';
-->
