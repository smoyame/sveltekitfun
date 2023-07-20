<script>
	let clientName = 'Friends of the Earth';
	let clientSettings = {
		basic: 'BASIC TEST',
		monetary: 'MONETARY TEST'
	};
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
				<fieldset class="fieldset t__fieldset">
					<h3 class="fset__heading typelvl-c">{clientSettings.basic}</h3>
				</fieldset>
				<fieldset class="fieldset t__fieldset">
					<h3 class="fset__heading typelvl-c">{clientSettings.monetary}</h3>
				</fieldset>
			</div>
		</div>
		<div class="t__codeareas">
			<fieldset class="fieldset">
				<h2 class="codearea__heading typelvl-b">Enter and retrieve your HTML</h2>
				<div class="code-wrapper">
					<div class="input-card code-area">
						<h3 class="typelvl-c">Input</h3>
						<textarea name="input" id="input" class="input" />
						<button id="inputBtn" class="inputBtn">Update my HTML</button>
					</div>
					<div class="output-card code-area">
						<h3 class="typelvl-c">Output</h3>
						<textarea name="output" id="output" class="output" />
						<button id="outputBtn" class="outputBtn">Copy new HTML</button>
					</div>
				</div>
			</fieldset>
		</div>
	</section>
</div>
