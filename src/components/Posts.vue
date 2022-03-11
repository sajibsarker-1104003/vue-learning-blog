<template>
	<div class="posts">
		<button class="load">See More</button>
	</div>
</template>

<script>
export default {
	// eslint-disable-next-line vue/multi-word-component-names
	name: 'posts'
}
</script>

<style lang="scss" scoped>
.posts {
	width: 100%;
	max-width: 1280px;
	
	margin: 50px auto;
	.load {
		display: block;
		width: 100%;
		max-width: 250px;
		height: 50px;
		margin: 0 auto;
		outline: none;
		border: none;
		border-radius: 15px;
		appearance: none;
		background-color: #FFCE00;
		box-shadow: 3px 3px 8px 0px rgba(0, 0, 0, 0.2);
		color: #171717;
		font-family: 'Rockwell', serif;
		font-size: 28px;
		padding-top: 7px;
		box-sizing: border-box;
	}
}
</style>