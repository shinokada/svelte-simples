<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Buildkite';
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
  ><title>Buildkite</title><path
    d="M23.613 8.143l-7.668-3.856v7.712l7.668-3.855zM8.166 15.857V8.143L.387 4.287V12l7.78 3.857zM.183 3.958a.382.382 0 01.377-.017l7.606 3.771 7.607-3.771a.386.386 0 01.346 0l7.668 3.857a.386.386 0 01.213.345v7.71a.388.388 0 01-.213.346l-7.668 3.86a.389.389 0 01-.562-.345v-7.09l-7.219 3.58a.392.392 0 01-.344 0L.215 12.346A.387.387 0 010 12V4.287a.385.385 0 01.183-.329z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Buildkite';
-->
