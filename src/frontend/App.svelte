<script lang="ts">
	export let name: string;
	const STATIC_DIR = "/_static";
</script>

<main>
	<h1>Hello {name}</h1>
	<img alt="logos" src="{STATIC_DIR}/images/logos.svg"/>
</main>

<style>
	main {
		display: grid;
		width: 100vw;
		height: -webkit-fill-available;
		align-content: center;
		justify-items: center;
		background-color: #FCF6F0;
	}

	h1 {
		margin: 0;
		text-align: center;
		color: #ff784b;
		font-size: 96pt;
		background-clip: text;
		-webkit-background-clip: text;
		-webkit-text-fill-color: transparent;
		background-image: linear-gradient(45deg, #ff784b 0%, #be2e2e 33%, #4328ab 66%, #0f2677 100%);
		opacity: 0.8;
	}

</style>