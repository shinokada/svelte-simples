<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Instructure';
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
  ><title>Instructure</title><path
    d="m11.996 0-5.11 2.878L12 5.76l5.115-2.878ZM6.032 3.36.918 6.237 6.036 9.12l5.115-2.879Zm11.929 0-5.112 2.878 5.115 2.882 5.118-2.879zM12 11.52.918 17.76 12 24l11.082-6.241Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'Instructure';
-->
