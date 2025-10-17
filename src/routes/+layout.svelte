<script lang="ts">
	import Nav from '$lib/components/nav.svelte';
	import '../app.css';
</script>

<div class="min-h-screen">
	<!-- Fixed navbar at top -->
	<nav class="fixed top-0 left-0 right-0 z-50 bg-white shadow-md">
		<Nav />
	</nav>
	
	<!-- Main content with padding to account for fixed navbar -->
	<main class="pt-16">
		<slot />
	</main>
</div>

