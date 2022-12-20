<script>
export let href
export let primary = undefined
</script>

<a class="button h5 lh2" class:button--primary={primary} {href}><slot /></a>

<style>
.button {
  display: block;
  padding: calc(1rem - 1px) calc(1.5rem - 1px);
  border: 1px solid;
  border-radius: 9999px;
  min-width: 8rem;
  text-align: center;
}

.button:hover {
  color: var(--bg-color);
  background-color: var(--color);
  border-color: transparent;
}

.button--primary {
  color: var(--bg-color);
  background-color: var(--color);
  border-color: transparent;
}
</style>
