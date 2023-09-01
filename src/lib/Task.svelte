<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Task';
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
  ><title>Task</title><path
    d="M1.857 18.013 11.736 24V12.456L1.857 6.468Zm20.286 0V6.468l-9.879 5.988V24Zm-.246-12.014L12 0 2.103 5.999 12 11.998Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'Task';
-->
