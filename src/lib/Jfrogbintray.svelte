<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Jfrogbintray';
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
  ><title>JFrog Bintray</title><path
    d="M2.617 22.316h18.766V24H2.617zm15.88-12.632l-5.655 5.655V3.249l1.744 1.743L15.79 3.79 12 0 8.21 3.79l1.204 1.203 1.744-1.804v12.15L5.504 9.686H7.97V8H2.617v5.354H4.3v-2.527L12 18.526l7.698-7.699v2.527h1.685V8H16.03v1.684z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Jfrogbintray';
-->
