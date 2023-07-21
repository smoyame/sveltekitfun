<script lang="ts">
	import InputWrapper from '$lib/components/nano/InputWrapper.svelte';
	export let id: string;
	export let label: string;
</script>

<InputWrapper type="textarea">
	<label for={id} class={'label--settings lsett__' + id}>{label}</label>
	<textarea name={id} {id} class={id + ' textarea'} />
</InputWrapper>

<style>
	textarea {
		resize: none;
	}
</style>
