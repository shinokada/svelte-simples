<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Adroll';
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
  ><title>Adroll</title><path
    d="M24 12c0-6.01-4.727-10.886-10.886-10.886a10.863 10.863 0 0 0-9.508 5.578L8.914 12c0-2.323 1.958-4.2 4.2-4.2 2.377 0 4.2 1.877 4.2 4.2s-1.836 4.2-4.2 4.2H4.065A4.07 4.07 0 0 0 0 20.266v2.62h13.114C19.232 22.886 24 18.01 24 12"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'Adroll';
-->
