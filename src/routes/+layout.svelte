<script lang="ts">
	import Nav from '$lib/components/nav.svelte';
	import '../app.css';
</script>

<div class="mx-4">
	<div class="mt-4 z-0 overflow-visible">
		<Nav />
	</div>
	<div class="overflow-visible" style="margin-top: -172px;">
		<slot />
	</div>
</div>

