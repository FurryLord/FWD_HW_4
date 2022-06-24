<script>
	import NavBar from "../../my-portfolio/src/navBar.svelte";
	import CvContent from "./CV_content.svelte";
</script>

<body>
	<NavBar/>
	<CvContent/>
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
