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
  ><title>Google Nearby</title><path
    d="M6.5459 12.0003L12.001 6.545l5.4541 5.4552-5.4541 5.454zm16.9763-1.154L13.158.48a1.635 1.635 0 00-2.314 0L.4778 10.8462a1.629 1.629 0 000 2.305L10.848 23.5226a1.629 1.629 0 002.304 0l10.3702-10.3712a1.629 1.629 0 000-2.305zM12 20.7263l-8.7272-8.7281L12 3.27l8.7272 8.7282z"
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
