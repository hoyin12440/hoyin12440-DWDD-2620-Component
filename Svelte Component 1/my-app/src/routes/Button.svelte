<script>
	export let name = "Default";
	export let type = "regular";
</script>


{#if type=="regular"}
	<button class="bg-white hover:bg-black px-10 py-2 rounded-3xl">{name}</button>
{/if}

{#if type=="disabled"}
	<button class="bg-black hover:bg-white px-10 py-2 rounded-3xl">{name}</button>
{/if}