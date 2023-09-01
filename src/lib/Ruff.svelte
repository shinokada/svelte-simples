<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Ruff';
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
  ><title>Ruff</title><path
    d="m21.683 11.593-8.51-2.14 8.34-9.066a.23.23 0 0 0-.29-.352L2.252 11.62a.227.227 0 0 0-.108.226.23.23 0 0 0 .164.19l8.497 2.497-8.35 9.08a.228.228 0 0 0-.007.303.227.227 0 0 0 .3.047l19-11.953a.228.228 0 0 0 .105-.23.225.225 0 0 0-.172-.187z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'Ruff';
-->
