<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Nucleo';
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
  ><title>Nucleo</title><path
    d="M12.025 0a3.868 3.868 0 00-1.964.525L1.354 5.55V6.5h15.853a3.9 3.9 0 003.463-2.115L13.922.508A3.868 3.868 0 0012.025 0zm9.81 5.072L13.91 18.801a3.9 3.9 0 00.1 4.056l6.734-3.908a3.865 3.865 0 001.914-3.35V5.55l-.822-.477zM1.46 7.848a3.9 3.9 0 00-.117.004l.017 7.787a3.868 3.868 0 001.946 3.334L12.008 24l.824-.475-7.926-13.73A3.9 3.9 0 001.46 7.848zM11.992 9.1a2.6 2.6 0 00-2.584 2.6 2.6 2.6 0 002.6 2.599 2.6 2.6 0 002.6-2.6 2.6 2.6 0 00-2.6-2.6 2.6 2.6 0 00-.016 0Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Nucleo';
-->
