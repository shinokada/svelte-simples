<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Vonage';
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
  ><title>Vonage</title><path
    d="M9.279 11.617l-4.54-10.07H0l6.797 15.296a.084.084 0 0 0 .153 0zm9.898-10.07s-6.148 13.868-6.917 15.565c-1.838 4.056-3.2 5.07-4.588 5.289a.026.026 0 0 0 .004.052h4.34c1.911 0 3.219-1.285 5.06-5.341C17.72 15.694 24 1.547 24 1.547z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Vonage';
-->
