<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Kuula';
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
  ><title>Kuula</title><path
    d="M12 0C5.388 0 0 5.388 0 12s5.388 12 12 12 12-5.388 12-12S18.612 0 12 0Zm0 2.547A9.433 9.433 0 0 1 21.453 12 9.433 9.433 0 0 1 12 21.453 9.433 9.433 0 0 1 2.547 12 9.433 9.433 0 0 1 12 2.547Zm-.606 5.366 4.372-.693 2.01 3.944-3.13 3.13-3.944-2.01z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'Kuula';
-->
