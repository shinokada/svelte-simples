<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Quarkus';
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
  ><title>Quarkus</title><path
    d="M3.981 0A3.993 3.993 0 0 0 0 3.981V20.02A3.993 3.993 0 0 0 3.981 24h10.983L12 16.8l-2.15 4.546H3.98c-.72 0-1.327-.608-1.327-1.327V3.98c0-.72.608-1.327 1.327-1.327h16.04c.72 0 1.327.608 1.327 1.327v16.04c0 .72-.608 1.327-1.327 1.327h-3.48L17.63 24h2.388A3.993 3.993 0 0 0 24 20.019V3.98A3.993 3.993 0 0 0 20.019 0zm4.324 4.217v3.858l3.341-1.93zm7.39 0l-3.341 1.929 3.34 1.929zM12 6.35L8.305 8.483 12 10.617l3.695-2.134zM8.104 8.832v4.266l3.695 2.133v-4.266zm7.792 0L12.2 10.965v4.266l3.695-2.133zm-8.146.204l-3.34 1.93 3.34 1.928zm8.5 0v3.858l3.34-1.929zm-8.146 4.47v3.859l3.341-1.93zm7.792 0l-3.341 1.93 3.34 1.929z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-simples.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Quarkus';
-->
