<script>
import Copy from '$lib/Copy.svelte'
</script>

<footer class="px1 py2 md:p2">
  <Copy fullwidth>
    <p
      >&copy; {new Date().getFullYear()}
      Tablo Demo <span class="inlineblock mx05 gray lum80">|</span> Built with
      <a href="https://tablogdemo.vercel.app/">Tablo Theme</a>
      for SvelteKit by
      <a href="https://www.lemmonjuice.com/">Lemmon Juice</a></p
    >
  </Copy>
</footer>
