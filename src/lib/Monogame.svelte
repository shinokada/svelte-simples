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
  ><title>MonoGame</title><path
    d="M24 10.356V7.083a7.083 7.083 0 0 0-12-5.098A7.083 7.083 0 0 0 0 7.083v9.834A7.083 7.083 0 0 0 7.083 24h9.834a7.083 7.083 0 0 0 7.07-7.51H24v-4.332H9.834v4.332h9.834v.427a2.751 2.751 0 0 1-2.751 2.751H7.083a2.751 2.751 0 0 1-2.751-2.751V7.083a2.751 2.751 0 1 1 5.502 0v3.273h4.332V7.083a2.751 2.751 0 1 1 5.502 0v3.273z"
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
