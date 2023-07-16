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
  ><title>Elastic Stack</title><path
    d="M1.875 0C.839 0 0 .84 0 1.875v4.792h24V1.875C24 .839 23.16 0 22.125 0zM0 8.889v6.222h24V8.89zm0 8.444v4.792C0 23.161.84 24 1.875 24h9v-6.667zm13.125 0V24h9C23.161 24 24 23.16 24 22.125v-4.792z"
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
