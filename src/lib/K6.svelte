<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'K6';
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
  ><title>k6</title><path
    d="M24 23.646H0L7.99 6.603l4.813 3.538L19.08.354Zm-8.8-3.681h.052a2.292 2.292 0 0 0 1.593-.64 2.088 2.088 0 0 0 .685-1.576 1.912 1.912 0 0 0-.66-1.511 2.008 2.008 0 0 0-1.37-.59h-.04a.716.716 0 0 0-.199.027l1.267-1.883-1.01-.705-.477.705-1.22 1.864c-.21.31-.386.582-.495.77-.112.2-.21.41-.29.625a1.942 1.942 0 0 0-.138.719 2.086 2.086 0 0 0 .676 1.558c.422.411.989.641 1.578.64Zm-5.365-2.027 1.398 1.978h1.496l-1.645-2.295 1.46-2.029-.97-.671-.427.565-1.314 1.853v-3.725l-1.31-1.068v7.37h1.31v-1.98Zm5.367.792a.963.963 0 1 1 0-1.927h.009a.941.941 0 0 1 .679.29.897.897 0 0 1 .29.668.978.978 0 0 1-.977.967Z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'K6';
-->
