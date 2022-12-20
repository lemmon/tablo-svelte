<script>
export let bigger = undefined
export let fullwidth = undefined
export let align = undefined
export let textalign = undefined
</script>

<div
  class="copy {bigger ? 'h5 sd:h4' : 'h6 sd:h5'} lh2"
  class:copy--fullwidth={fullwidth}
  class:copy--center={align === 'center'}
  class:copy--right={align === 'right'}
  class:ac={textalign === 'center'}
  class:ar={textalign === 'right'}
>
  <slot />
</div>
