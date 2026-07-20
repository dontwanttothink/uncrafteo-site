<script lang="ts">
	import { page } from "$app/state";
</script>

<main>
	<h1>Oops.</h1>
	<p>
		Se produjo un error {page.status}. En inglés, ese código significa “{page
			.error?.message ?? "❓"}”.
	</p>
	<p><a href="/">Regresa al inicio 🧚.</a></p>
</main>

<style>
	main {
		text-align: center;
	}
</style>
