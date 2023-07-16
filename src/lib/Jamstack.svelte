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
  ><title>Jamstack</title><path
    d="M12 0C5.365 0 0 5.364 0 12s5.365 12 12 12 12-5.364 12-12V0zm.496 3.318h8.17v8.17h-8.17zm-9.168 9.178h8.16v8.149c-4.382-.257-7.904-3.767-8.16-8.149zm9.168.016h8.152a8.684 8.684 0 01-8.152 8.148z"
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
