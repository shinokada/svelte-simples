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
  ><title>Keystone</title><path
    d="M4.5 0A4.5 4.5 0 000 4.5v15A4.5 4.5 0 004.5 24h15a4.5 4.5 0 004.5-4.5v-15A4.5 4.5 0 0019.5 0zm5.47 14.789v3.586H6.744V5.692H9.97v5.45h.167l4.218-5.45h3.463l-4.385 5.599 4.64 7.084h-3.788l-3.2-5.001z"
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
