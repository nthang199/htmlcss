<template>
	<div class="content__left">
		<div class="content__left__aboutme">
			<div class="content__left__aboutme__title">
				<h2>About me</h2>
				<p class="content__left__aboutme__title-titleimg">Photo of me:</p>
				<img src="http://kienthuckhoahoc.org/images/kt/70/0/arnh.jpg" alt="" />
				<p class="content__left-description">
					Some text about me culpa qui ofical desenunt mollit anim
				</p>
			</div>
		</div>
		<div class="content__left__moretext">
			<h2>More text</h2>
			<p class="content__left-description">
				Lorem ipsum dolor sit..
			</p>
			<img src="http://kienthuckhoahoc.org/images/kt/70/0/arnh.jpg" alt="" />
			<img src="http://kienthuckhoahoc.org/images/kt/70/0/arnh.jpg" alt="" />
			<img src="http://kienthuckhoahoc.org/images/kt/70/0/arnh.jpg" alt="" />
		</div>
	</div>
</template>

<script>
export default {
	name: "content-left",
	data() {
		return {};
	},
};
</script>

<style scoped>
/*   class common */
.content__left {
	width: 26%;
	height: 96%;
	background-color: #c9c9c9;
	padding: 2%;
	text-align: left;
	float: left;
}
/*    about me */
.content__left__aboutme__title {
	display: table;
}
.content__left__aboutme__title-titleimg {
	font-size: 16px;
	font-weight: 600;
	text-align: left;
	padding: 20px 0;
}
.content__left__aboutme__title img {
	width: 100%;
	height: 100%;
	background-color: #646262;
}
.content__left-description {
	font-size: 15px;
	font-weight: 450;
	padding-top: 10px;
}
/*    more text */
.content__left__moretext {
	padding-top: 20px;
}
.content__left__moretext img {
	padding-top: 20px;
	width: 100%;
	height: auto;
}
@media only screen and (max-width: 600px) {
	.content__left {
		width: 96%;
		padding: 2%;
		background-color: #fff;
	}
	.content__left__aboutme__title-description {
		text-align: center;
	}
	.content__left__moretext img {
		height: auto;
	}
}
</style>
