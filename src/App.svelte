<script lang="ts">
    import WorldMap from "./assets/worldMap.svelte";

	let input:string;


</script>

<main class="bg-gray-500 w-scren h-screen grid place-content-center">

	<div class="w-fit h-fit flex flex-col gap-4 items-center">

	<WorldMap guess={ input }/>

	<input bind:value={input} type="text" name=""  class="">

		<p>{input}</p>

	</div>
</main>

