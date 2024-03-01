<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Revealdotjs';
</script>

<svg
  viewBox="0 0 24 24"
  width={size}
  height={size}
  fill={color}
  {...$$restProps}
  {role}
  aria-label={ariaLabel}
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
  ><title>reveal.js</title><path
    d="M4.271 1.352a.774.774 0 0 0-.787.775v19.761c0 .49.45.857.93.758l6.676-1.382-2.77-.614-3.675.762V2.607l3.101.686 2.777-.574-6.097-1.35a.774.774 0 0 0-.155-.017zm15.315.002L5.145 4.344v15.092l14.43 3.195a.774.774 0 0 0 .94-.758V2.111a.773.773 0 0 0-.93-.757zM2.984 4.79l-2.367.49A.774.774 0 0 0 0 6.04v11.639a.774.774 0 0 0 .607.754l2.377.525V4.791zm18.034.252V6.23l1.822.405v11.011l-1.822.377v1.186l2.365-.49A.774.774 0 0 0 24 17.96V6.322a.774.774 0 0 0-.607-.754l-2.375-.525z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Revealdotjs';
-->
