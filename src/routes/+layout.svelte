<script lang="ts">
	import favicon from "$lib/assets/favicon.jpeg";
	import "../app.css";

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>UNcrafteo</title>
	<meta
		name="description"
		content="De estudiantes de la UNAL, un servidor de Minecraft con mods."
	/>
</svelte:head>

{@render children()}
