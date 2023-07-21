<script lang="ts">
	import TunerSettings from '$lib/components/TunerSettings.svelte';
	import Dropdown from '$lib/components/micro/Dropdown.svelte';
	import Text from '$lib/components/micro/Text.svelte';
	import Option from '$lib/components/nano/Option.svelte';

	let clientName = 'Friends of the Earth';
</script>

<div class="sidebar">
	<footer class="sidebar__footer">&copy; 2023 | SMOYA.ME</footer>
</div>
<div class="tuner-wrapper">
	<header class="tuner__header">
		<p class="tw__overline overline">Formatting Email Code For</p>
		<h1 class="tw__heading typelvl-a">{clientName}</h1>
	</header>
	<section class="tuner__section section">
		<div class="t__settings">
			<h2 class="tuner__heading typelvl-b">Settings</h2>
			<div class="tuner__inputs">
				<TunerSettings groupname="775643453455645677777">
					<Text id="slug" label="This is the input label..." />
					<Text id="previewtext" label="What is your preview text?" />
					<Dropdown id="hpc" label="What HPC level is needed?">
						<Option options={['two', 'three', 'four']} />
					</Dropdown>
				</TunerSettings>

				<TunerSettings groupname="Mone444tary">
					<Text id="TESTGO44OD" label="TTESTY" />
				</TunerSettings>
			</div>
		</div>
		<div class="t__codeareas">
			<fieldset class="fieldset ca_fieldset">
				<h2 class="codearea__heading typelvl-b">Replace</h2>
				<div class="code-wrapper">
					<div class="input-card code-area">
						<label class="typelvl-c" for="input">Input</label>
						<textarea name="input" id="input" class="input" />
						<button id="inputBtn" class="inputBtn">Update my HTML</button>
					</div>
					<div class="output-card code-area">
						<label class="typelvl-c" for="output">Output</label>
						<textarea name="output" id="output" class="output" />
						<button id="outputBtn" class="outputBtn">Copy new HTML</button>
					</div>
				</div>
			</fieldset>
		</div>
	</section>
</div>
