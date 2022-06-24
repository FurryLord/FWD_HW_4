<script lang="ts">
	import NavBar from "./navBar.svelte";
	import MainContent from "./mainContent.svelte";
</script>

<body>
	<NavBar />
	<MainContent />
</body>

<style>
	* {
		font-family: "Consolas";
		color: aliceblue;
	}
	body {
		max-width: 1920px;
		margin: 0 auto;
		background-color: #53359f;
	}
</style>
