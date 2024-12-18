<script lang="ts">
	import '../app.css';
	import Header from '$lib/components/Header.svelte'; // Import the Header component
	let { children } = $props();
</script>

<Header title="Welcome to My Website" />

{@render children()}
