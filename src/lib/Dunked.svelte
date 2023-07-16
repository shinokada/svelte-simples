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
  ><title>Dunked</title><path
    d="M13.799 0v19.8599A4.2002 4.2002 0 0018.0003 24h4.2002V4.1411A4.2002 4.2002 0 0017.9992 0H13.798zM6.2983 15.0014a4.5008 4.5008 0 00-4.4988 4.3906v.2224a4.5008 4.5008 0 008.9986 0v-.2154a4.5008 4.5008 0 00-4.4998-4.3986z"
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
