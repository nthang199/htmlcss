<template>
	<div class="content__right">
		<HomeContentRightTitle></HomeContentRightTitle>
		<HomeContentRightTitle></HomeContentRightTitle>
	</div>
</template>

<script>
import HomeContentRightTitle from "./HomeContentRightTitle";
export default {
	name: "content-right",
	data() {
		return {};
	},
	components: { HomeContentRightTitle },
};
</script>

<style>
.content__right {
	width: 66%;
	height: 96%;
	padding: 2%;
	text-align: left;
	float: right;
}
@media only screen and (max-width: 600px) {
	.content__right {
		width: 96%;
		padding: 2%;
		text-align: left;
		margin-top: 20px;
	}
}
</style>
