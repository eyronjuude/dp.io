<script>
	import FacebookLogin from "./FacebookLogin.svelte";
	import Dashboard from "./Dashboard.svelte";
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