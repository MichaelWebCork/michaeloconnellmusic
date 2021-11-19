<script>
	import '../app.css';
	import Navbar from "$lib/components/Navbar.svelte";
</script>

<main class="main">
	<Navbar/>
	<slot />
</main>

<style>
.main {
	padding: 15px 20px;
	max-width: 1200px;
	margin: 0 auto;
}
</style>