<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Crayon';
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
  ><title>Crayon</title><path
    d="M1.9485 16.5624C3.1842 17.7981 4.8 18.4159 6.416 18.4159c1.6158 0 3.2317-.6179 4.4673-1.8535l5.798-5.798-1.4257-1.4258-5.798 5.7505c-1.6634 1.6634-4.3723 1.6634-6.0832 0l-.095-.095c-1.6635-1.6634-1.6635-4.3723 0-6.0832l.095-.095c1.6633-1.6635 4.3723-1.6635 6.0832 0l.4752.5227 1.4258-1.4258-.4753-.5227c-2.4713-2.4713-6.5109-2.4713-8.9822 0l-.0475.1425c-2.4713 2.4713-2.4713 6.511 0 8.9823zm20.0556-9.1248c-1.2357-1.2357-2.8515-1.8535-4.4674-1.8535-1.6158 0-3.2317.6179-4.4673 1.8535l-5.798 5.798 1.4257 1.4258 5.798-5.7505c1.6634-1.6634 4.3723-1.6634 6.0832 0l.095.095c1.6634 1.6634 1.6634 4.3723 0 6.0832l-.095.095c-1.6633 1.6635-4.3723 1.6635-6.0832 0l-.4752-.4752-1.4258 1.4258.4753.4752c2.4713 2.4713 6.5109 2.4713 8.9822 0l.095-.095c2.4713-2.4713 2.4713-6.511 0-8.9823-.0475 0-.1425-.095-.1425-.095z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Crayon';
-->
