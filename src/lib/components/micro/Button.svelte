<script lang="ts">
	export let copy: string = 'Button Text';
	export let id: string = 'default';
</script>

<button type="button" id={id + 'Btn'} class={'button ' + id}>
	{copy}
</button>
