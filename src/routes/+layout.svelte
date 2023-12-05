<script>
	import '../app.css';
</script>

<div class="app">
  <main class="container mx-auto">
    <slot />
  </main>
</div>

<style lang='postcss'>
	:global(html){
		background-color: theme(colors.red.100);
	}
</style>
