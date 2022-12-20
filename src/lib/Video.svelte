<script>
export let src = undefined
export let fullwidth = false
export let caption = undefined
</script>

<figure class="figure video" class:figure--fullwidth={fullwidth}>
  <iframe
    class="block w100 ha"
    style="aspect-ratio: 16/9;"
    {src}
    title="Video player"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
  />
  {#if caption}
    <figcaption class="mt05 h6 lh2 ac">{caption}</figcaption>
  {/if}
</figure>
