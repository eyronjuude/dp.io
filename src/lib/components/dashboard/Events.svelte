<script>
	import Trash from "$lib/icons/Trash.svelte";
</script>

{#each [...Array(3).keys()].map(i => i+1) as num}
    <div class="flex card">
        <div class="grow-0 p-4">Event {num}</div>
        <div class="grow"></div>
        <Trash />
    </div>
{/each}