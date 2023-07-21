<script lang="ts">
	import InputWrapper from '$lib/components/nano/InputWrapper.svelte';
	export let id: string;
	export let radioGroup: string;
	export let label: string;
</script>

<InputWrapper type="radio">
	<label for={id} class={'label--settings ls__' + id}>{label}</label>
	<input type="radio" name={radioGroup} {id} class={id + ' radio'} value={label.toLowerCase()} />
</InputWrapper>
