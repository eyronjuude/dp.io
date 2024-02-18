<script>
	import PopularEvents from './PopularEvents.svelte';
</script>

<h2>Join a DP blast event!</h2>

<input id="public_event_join" type="button" value="Search for a public event" />
<input id="private_event_join" type="button" value="Insert a private event key" />

<h2>Most popular public events</h2>

<PopularEvents />