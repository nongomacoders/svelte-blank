<script>
	import Heading from './Heading.svelte'
	let days = ["mon", "tues", "wed", "thurs", "fri", "sat", "sun"];

</script>
<Heading/>
<main>
{#each days as day}
<button class="btn blue">{day}</button>
<br>
{/each}


</main>

<style>

</style>