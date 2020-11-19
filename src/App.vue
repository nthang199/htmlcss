<template>
	<div id="app">
		<Home></Home>
	</div>
</template>

<script>
import Home from "./views/home/Home";

export default {
	name: "App",
	components: {
		Home,
	},
	data() {
		return {};
	},
};
</script>

<style>
* {
	margin: 0;
	padding: 0;
}
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	overflow: scroll;
}
</style>
