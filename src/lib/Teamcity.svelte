<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Teamcity';
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
  ><title>TeamCity</title><path
    d="m0 0v24h24v-24zm2.664 2.964h7.48v1.832h-2.748v7.196h-1.984v-7.196h-2.748zm9.328 18h-9v-1.5h9zm5.56391-9.21826a4.62 4.62 0 0 1 -2.03591.37426 4.556 4.556 0 0 1 -4.628-4.616v-.024a4.584 4.584 0 0 1 4.708-4.668 4.65561 4.65561 0 0 1 3.56 1.388l-1.264 1.456a3.33594 3.33594 0 0 0 -2.312-1.02 2.67116 2.67116 0 0 0 -2.616 2.8v.028a2.68058 2.68058 0 0 0 2.616 2.836 3.22606 3.22606 0 0 0 2.376-1.056l1.264 1.276a4.61947 4.61947 0 0 1 -1.66809 1.22573z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Teamcity';
-->
