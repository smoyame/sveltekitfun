<script lang="ts">
	import InputWrapper from '$lib/components/nano/InputWrapper.svelte';
	export let id: string;
	export let label: string;
</script>

<InputWrapper type="text">
	<label for={id} class={'label--settings ls__' + id}>{label}</label>
	<input type="text" name={id} {id} class={id} />
</InputWrapper>
