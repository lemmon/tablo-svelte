<script>
export let gap = 2
export let valign = undefined
export let fullwidth = undefined
</script>

<div
  class="block span1 px1 py2 md:p2 col"
  class:self-start={valign === 'top'}
  class:self-end={valign === 'bottom'}
  class:block--fullwidth={fullwidth}
  style="--gap: {gap}rem; gap: var(--gap);"
>
  <slot />
</div>

<style>
.block--fullwidth {
  flex-basis: 100%;
}
</style>
