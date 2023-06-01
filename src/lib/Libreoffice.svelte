<script>
  export let size = '24';
  export let role = 'img';
  export let color = '#1877F2';
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
  ><title>LibreOffice</title><path
    d="M16.365 0a.597.597 0 00-.555.352.582.582 0 00.128.635l4.985 4.996a.605.605 0 00.635.133.59.59 0 00.363-.53V.577A.605.605 0 0021.335 0zM2.661 0a.59.59 0 00-.582.59v22.82a.59.59 0 00.582.59h18.67a.59.59 0 00.59-.59V8.716a.59.59 0 00-.17-.42L13.674.182a.59.59 0 00-.42-.181zm.59 1.184h9.754l7.733 7.77v13.863H3.251z"
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
