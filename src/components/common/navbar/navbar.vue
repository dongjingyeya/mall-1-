<template>
	<div class="navbar">
		<div class="left"><slot name="left"></slot></div>
		<div class="center"><slot name="center"></slot></div>
		<div class="right"><slot name="right"></slot></div>
	</div>
</template>

<script>
	export default{
		name:'navbar'
	}
</script>

<style>
	.navbar{
		display: flex;
		height: 44px;
		line-height: 44px;
		background-color: pink;
	}
	.left, .right{
		width: 60px;
	}
	.center{
		flex: 1;
		text-align: center;
		font-size: 20px;
		color: #fff;
	}
</style>
