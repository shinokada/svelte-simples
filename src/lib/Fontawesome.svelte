<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Fontawesome';
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
  ><title>Font Awesome</title><path
    d="M24 .857v18c-3.375 1.232-4.393 1.714-6.375 1.714-3.375 0-4.66-1.714-8.036-1.714-1.071 0-1.928.214-2.732.429v-3.429c.804-.214 1.661-.428 2.732-.428 3.375 0 4.661 1.714 8.036 1.714 1.071 0 1.875-.16 2.946-.482V5.518C19.5 5.839 18.696 6 17.625 6c-3.375 0-4.66-1.714-8.036-1.714-2.732 0-4.017 1.125-6.16 1.553v16.447A1.693 1.693 0 011.714 24 1.693 1.693 0 010 22.286V1.714A1.693 1.693 0 011.714 0 1.693 1.693 0 013.43 1.714v.697C5.572 1.982 6.857.857 9.589.857c3.375 0 4.661 1.715 8.036 1.715 1.982 0 3-.483 6.375-1.715Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Fontawesome';
-->
