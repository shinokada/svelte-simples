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
  ><title>Namebase</title><path
    d="M23.0978 2.406c0 1.3288-1.0516 2.406-2.3488 2.406s-2.3487-1.0772-2.3487-2.406S19.4519 0 20.7491 0s2.3487 1.0772 2.3487 2.406zm-11.5089.5415C5.6868 2.9475.9022 7.8488.9022 13.8948V24h6.5764V13.8948c0-2.3254 1.8403-4.2105 4.1103-4.2105s4.1103 1.8851 4.1103 4.2105V24h6.5764V13.8948c0-6.046-4.7846-10.9473-10.6867-10.9473z"
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
