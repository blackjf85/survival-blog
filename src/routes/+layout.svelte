<script>
	import '../app.css';
	import Navbar from '../lib/components/Navbar.svelte';
</script>

<Navbar />

<main id="main" class="container py-4 mx-auto flex justify-center items-center">
	<slot />
</main>
