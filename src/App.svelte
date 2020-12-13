<script lang="ts">
	import Tailwindcss from "./Tailwindcss.svelte";
	export let name: string;
</script>

<Tailwindcss />

<main class="text-center p-4 max-w-xs sm:max-w-none my-0 mx-auto">
	<h1 class="uppercase text-6xl font-thin text-red-500">Hello {name}!</h1>
	<p>
		Visit the
		<a
			class="text-blue-700 hover:underline"
			href="https://svelte.dev/tutorial">Svelte tutorial</a>
		to learn how to build Svelte apps.
	</p>
</main>
