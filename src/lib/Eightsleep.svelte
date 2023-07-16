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
  ><title>Eight Sleep</title><path
    d="M19.847 7.28V4.105A4.104 4.104 0 0 0 15.745 0H8.258a4.104 4.104 0 0 0-4.105 4.102v3.183a4.092 4.092 0 0 0 2.415 3.738v.588a4.102 4.102 0 0 0-2.415 3.738v4.546A4.104 4.104 0 0 0 8.255 24h7.488a4.104 4.104 0 0 0 4.104-4.104v-4.553a4.102 4.102 0 0 0-2.415-3.738v-.587a4.102 4.102 0 0 0 2.415-3.738zM8.451 5.126c0-.818.662-1.482 1.48-1.483h4.133c.819 0 1.483.663 1.483 1.482v1.991c0 .819-.664 1.482-1.483 1.482H9.93a1.482 1.482 0 0 1-1.482-1.482l.003-1.99zm7.1 13.732c0 .818-.664 1.482-1.483 1.482H9.93a1.482 1.482 0 0 1-1.482-1.482v-2.752c0-.819.664-1.483 1.482-1.483h4.134c.819 0 1.483.664 1.483 1.483l.003 2.752z"
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
