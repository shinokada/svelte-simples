<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Hexlet';
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
  ><title>Hexlet</title><path
    d="M 19.774648,3.0422535 12,0 4.225352,3.0422535 12,5.7464789 Z m -3.042254,4.056338 V 13.521127 H 7.2676055 V 7.0985915 L 4.5633802,6.084507 V 24 H 7.2676055 V 16.225352 H 16.732394 V 24 H 19.43662 V 6.084507 Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'Hexlet';
-->
