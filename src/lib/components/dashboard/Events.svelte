{#each [...Array(3).keys()].map(i => i+1) as num}
    <div class="card p-4">Event {num}</div>
{/each}