<script>
  export let size = '24';
  export let role = 'img';
  export let color = '#1877F2';
</script>

<svg
  viewBox="0 0 24 24"
  width={size}
  height={size}
  fill={color}
  {...$$restProps}
  {role}
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
  ><title>Reason Studios</title><path
    d="M2.49 5.114l8.3-4.79a2.421 2.421 0 012.39-.017l.03.017 8.299 4.79c.74.427 1.2 1.212 1.211 2.065V16.79c0 .854-.451 1.645-1.184 2.08l-.027.016-8.299 4.79a2.42 2.42 0 01-2.39.017l-.03-.017-8.3-4.79a2.421 2.421 0 01-1.21-2.065V7.21c0-.855.45-1.645 1.184-2.08l.026-.016 8.3-4.79zM12 4.026L5.092 8.013v7.974L12 19.974V12l6.908-3.987z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-simples.codewithshin.com/)
## Props
@prop size = '24';
@prop role = 'img';
@prop color = '#1877F2';
## Event
- on:click
- on:keydown
- on:keyup
- on:focus
- on:blur
- on:mouseenter
- on:mouseleave
- on:mouseover
- on:mouseout
-->
