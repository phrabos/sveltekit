<script>
  import Footer from '$lib/footer.svelte';
  import Header from '$lib/header.svelte';
</script>

<Header />
<main>
  <slot></slot>
</main>
<Footer />