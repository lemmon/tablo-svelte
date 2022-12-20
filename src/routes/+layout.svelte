<script>
import '$lib/css/index.css'
import PageLoader from '$lib/PageLoader.svelte'
import PageHeader from '$lib/PageHeader.svelte'
import PageFooter from '$lib/PageFooter.svelte'
</script>

<PageLoader />

<PageHeader />

<main class="span1">
  <slot />
</main>

<PageFooter />
