<script lang="ts">
	import InputWrapper from '$lib/components/nano/InputWrapper.svelte';
	export let id: string;
	export let label: string;
</script>

<InputWrapper type="select">
	<label for={id} class={'label--settings ls__' + id}>{label}</label>
	<select name={id} {id} class={id}>
		<slot />
	</select>
</InputWrapper>
