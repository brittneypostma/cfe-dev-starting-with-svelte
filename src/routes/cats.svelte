<script>
export let cats;
export let prerender = true
</script>

<h1>This is a group of cats</h1>

{#each cats as cat}
<img src={cat.url} alt="cat" />
{/each}