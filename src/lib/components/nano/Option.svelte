<script lang="ts">
	export let options: Array<any> = ['First', 'Second', 'Third'];
</script>

{#each options as option}
	<option value={option}>{option}</option>
{/each}
