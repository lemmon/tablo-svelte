<script>
export let is = 'h1'
export let bigger = undefined
export let biggest = undefined
</script>

<header class="header">
  <svelte:element this={is} class="{biggest ? 'd1 sd:d2' : bigger ? 'h1 sd:d1' : is} lh1 lsh"><slot /></svelte:element>
</header>

<style>
.header {
  max-width: var(--copy-width);
}
</style>
