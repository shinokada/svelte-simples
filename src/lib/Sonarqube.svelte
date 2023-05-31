<script>
  export let size = '24';
  export let color = '#1877F2';
</script>

<svg
  role="img"
  viewBox="0 0 24 24"
  width={size}
  height={size}
  fill={color}
  class={$$props.class}
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
  ><title>SonarQube</title><path
    d="M15.685.386l-.465.766c3.477 2.112 6.305 5.27 7.966 8.89L24 9.67C22.266 5.887 19.313 2.59 15.685.386zM8.462.91l-.305 1.075c6.89 1.976 12.384 7.64 13.997 14.421l1.085-.258C21.535 8.977 15.735 2.997 8.462.909zM0 2.667v1.342c10.963 0 19.883 8.795 19.883 19.605h1.342c0-11.55-9.522-20.947-21.225-20.947z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-simples.codewithshin.com/)
## Props
@prop size = '24';
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
