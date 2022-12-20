<script>
export let src = undefined
export let srcset =
  src &&
  [480, 640, 800, 960, 1120, 1280, 1440, 1600]
    .map((w) => `${src.replace(/(?<=\.)\d+w(?=\.)/, `${w}w`)} ${w}w`)
    .join(', ')
export let fullwidth = false
export let contain = false
export let width = undefined
export let height = undefined
export let ratio = width && height ? `${width}/${height}` : 'auto'
export let caption = undefined
</script>

<figure class="figure image" class:figure--fullwidth={fullwidth}>
  <img
    class="block w100 h100 {contain ? 'object-contain' : 'object-cover'}"
    style="aspect-ratio: {ratio};"
    {src}
    {srcset}
    {width}
    {height}
    alt=""
  />
  {#if caption}
    <figcaption class="mt05 h6 lh2 ac">{caption}</figcaption>
  {/if}
</figure>
