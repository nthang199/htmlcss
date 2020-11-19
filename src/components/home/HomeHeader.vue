<template>
	<div class="header-home">
		<div class="header">
			<div class="header__title">
				<h1 class="header__title-h1">{{ headerInfo.title }}</h1>
				<p class="header__suntitle-p">{{ headerInfo.subtitle }}</p>
			</div>
		</div>
		<div class="header__navbar">
			<ul class="header__navbar__list">
				<li class="header__navbar__list-item">Link</li>
				<li class="header__navbar__list-item">Link</li>
				<li class="header__navbar__list-item">Link</li>
				<li class="header__navbar__list-item">Link</li>
			</ul>
		</div>
	</div>
</template>

<script>
export default {
	name: "home-header",
	props: { headerInfo: Object },
	data() {
		return {};
	},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
	margin: 0;
	padding: 0;
}
.header-home {
	color: #fff;
}
.header {
	width: 100%;
	height: 200px;
	background-color: #14a97f;
	display: flex;
	align-items: center;
	justify-content: center;
}
.header__suntitle-p {
	padding-top: 20px;
	font-size: 18px;
	font-weight: 400;
}
.header__navbar {
	width: 100%;
	/* height: 40px; */
	background-color: #000;
	display: flex;
	align-items: center;
}
.header__navbar__list {
	list-style-type: none;
	display: flex;
	height: 100%;
}
.header__navbar__list-item {
	padding: 10px 20px;
	font-weight: 500;
	width: 100%;
	display: flex;
	align-items: center;
}
.header__navbar__list-item:hover,
.header__navbar__list-item:active {
	background-color: rgb(117, 116, 116);
	transition: background-color 0.4s;
	cursor: pointer;
}
@media only screen and (max-width: 600px) {
	.header__navbar__list-item {
		display: table;
		padding: 10px 0;
		justify-content: center;
		text-align: center;
	}
	.header__navbar__list {
		display: table-column;
		height: 100%;
		width: 100%;
	}
}
</style>
