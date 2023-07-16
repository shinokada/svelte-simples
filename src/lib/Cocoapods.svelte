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
  ><title>CocoaPods</title><path
    d="M8.812 17.176c-2.968 0-4.956-2.308-4.956-5.176 0-2.705 1.776-5.176 4.91-5.176 2.407 0 3.856 1.445 4.207 3.357h3.95C16.479 6.427 13.51 3.42 8.718 3.42 3.131 3.42 0 7.523 0 12c0 4.57 3.295 8.58 8.766 8.58 4.58 0 7.549-2.822 8.18-6.272h-4.02c-.467 1.609-1.916 2.868-4.114 2.868zM24 12.068l-3.466 8.055-2.38-1.022 2.992-7.055-3.01-7.096 2.433-1.042Z"
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
