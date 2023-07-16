<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
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
  ><title>Chainlink</title><path
    d="M12 0L9.798 1.266l-6 3.468L1.596 6v12l2.202 1.266 6.055 3.468L12.055 24l2.202-1.266 5.945-3.468L22.404 18V6l-2.202-1.266-6-3.468zM6 15.468V8.532l6-3.468 6 3.468v6.936l-6 3.468z"
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
