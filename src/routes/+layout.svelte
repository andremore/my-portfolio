<script>
	import Navbar from '../lib/components/Navbar.svelte';
	import './styles.css';
</script>

<div class="mx-28">
	<Navbar />

	<main>
		<slot />
	</main>
</div>

<style lang="postcss">
	:global(html) {
		background-color: #191d26;
		color: #eafaff;
	}
</style>
