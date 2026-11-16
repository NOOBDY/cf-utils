<script lang="ts">
  import './layout.css';
  import favicon from '$lib/assets/favicon.svg';

  let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
<div class="mx-auto mt-10 w-full max-w-3xl px-5">
  {@render children()}
</div>
