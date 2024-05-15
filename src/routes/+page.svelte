<script>
	import FacebookLogin from "$lib/components/FacebookLogin.svelte";
	import Dashboard from "$lib/components/Dashboard.svelte";
	let login = false;
</script>

{#if login}
<div class="flex justify-center items-center">
	<FacebookLogin />
</div>

{:else}
<div class="flex flex-col p-8 gap-4 justify-center">
	<Dashboard />
</div>

{/if}