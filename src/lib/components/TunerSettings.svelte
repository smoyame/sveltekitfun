<script lang="ts">
	export let groupname: string;
</script>

<fieldset class="fieldset t__fieldset">
	<h3 class="fset__heading typelvl-c">{groupname}</h3>
	<div class="inputs-wrapper">
		<slot />
	</div>
</fieldset>
