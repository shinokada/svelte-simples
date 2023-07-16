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
  ><title>SPDX</title><path
    d="M0 0v24H8.222l2.089-2.373 2.09-2.374V13.2H18.978l2.51-2.488L24 8.223V0H12zm5.2 5.2h13.791L12.2 12c-3.735 3.74-6.838 6.8-6.896 6.8-.057 0-.104-3.06-.104-6.8zm8.4 8.8v10H24V14h-5.2z"
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
