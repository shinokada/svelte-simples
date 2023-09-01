<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Peakdesign';
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
  ><title>Peak Design</title><path
    d="m24 10.523-9.446 6.493-4.74-3.271 4.723-3.255 3.738 2.57 3.705-2.537zm-6.743 3.255-2.72-1.886-2.704 1.853 2.737 1.869zm-7.794-.284-3.738-2.57-3.706 2.554h-2.019l9.43-6.493 4.756 3.255zm-2.737-3.254 2.737 1.869 2.704-1.869-2.737-1.87z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'Peakdesign';
-->
