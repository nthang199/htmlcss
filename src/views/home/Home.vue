<template>
	<div class="home">
		<HomeHeader :headerInfo="headerInfo"></HomeHeader>
		<HomeContentLeft></HomeContentLeft>
		<HomeContentRight></HomeContentRight>
		<HomeFooter></HomeFooter>
	</div>
</template>

<script>
import HomeHeader from "../../components/home/HomeHeader";
import HomeFooter from "../../components/home/HomeFooter";
import HomeContentLeft from "../../components/home/HomeContentLeft";
import HomeContentRight from "../../components/home/HomeContentRight";
export default {
	name: "home",
	props: {},
	data() {
		return {
			headerInfo: { title: "My Website", subtitle: "With a flexible layout" },
		};
	},
	components: { HomeHeader, HomeContentLeft, HomeContentRight, HomeFooter },
};
</script>

<style></style>
