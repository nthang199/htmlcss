<template>
	<div class="content__right__titleheading">
		<h2>title heading</h2>
		<p class="content__right__titleimg">Title description, Dec 7,2020</p>
		<div class="content__right-img">
			<img src="http://kienthuckhoahoc.org/images/kt/70/0/arnh.jpg" alt="" />
		</div>
		<p class="content__right-description">Some text ...</p>
		<p class="content__right-description">
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores quis
			porro obcaecati magni, alias corporis id ea aperiam cumque incidunt
			nesciunt expedita impedit voluptatibus perferendis. Praesentium vero
			dolores placeat delectus.
		</p>
	</div>
</template>

<script>
export default {
	name: "content-right-titleheading",
	data() {
		return {};
	},
};
</script>

<style scoped>
.content__right__titleheading {
	padding-bottom: 40px;
}
.content__right__titleheading h2 {
	text-transform: uppercase;
}
.content__right__titleimg {
	font-size: 16px;
	font-weight: 600;
	text-align: left;
	padding: 20px 0;
}
.content__right__titleheading img {
	width: 100%;
}
.content__right-description {
	font-size: 15px;
	font-weight: 450;
	padding-top: 10px;
}
@media only screen and (max-width: 600px) {
}
</style>
