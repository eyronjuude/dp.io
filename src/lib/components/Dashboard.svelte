<script>
    import { Avatar } from '@skeletonlabs/skeleton';
	import Events from './dashboard/Events.svelte';
</script>

<Avatar
    class="self-center"
    width="w-32 md:w-60"
	border="border-4 border-surface-300-600-token hover:!border-primary-500"
	cursor="cursor-pointer"
/>

<h1 class="text-2xl md:text-4xl self-center">My Name Is Faker</h1>

<hr class="h-0.5 border-t-0 bg-neutral-100 dark:bg-white/10" />

<h1 class="text-2xl md:text-4xl">My Events</h1>

<div class="flex flex-col gap-4">
    <Events />
</div>