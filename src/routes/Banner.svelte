<script lang="ts">
    import { AppBar } from '@skeletonlabs/skeleton';
    import { Avatar } from '@skeletonlabs/skeleton';
</script>

<AppBar gridColumns="grid-cols-3" slotDefault="place-self-center" slotTrail="place-content-end">
	<svelte:fragment slot="lead">
        <Avatar background="bg-secondary-500" border="border-4 border-surface-300-600-token hover:!border-primary-500" cursor="cursor-pointer">
            :)
        </Avatar>
    </svelte:fragment>
	dp.io
	<svelte:fragment slot="trail">About dp.io</svelte:fragment>
</AppBar>
