<template>
	<view class="qiun-title-bar">
		<view class="qiun-title-dot"></view>
		<view class="qiun-title-text">{{title}}</view>
	</view>
</template>

<script>
export default {
	name: "title-bar",
	props: {
		title: {
			type: String,
			default: ''
		},
	},
	mounted() {
		
	},
	methods:{
	}
}
</script>


<style>
	.qiun-title-bar{
		display: flex;
		flex-direction: row !important;
		flex-wrap: nowrap;
		align-items: center;
		height: 40px;
	}
	
	.qiun-title-dot {
		border-radius: 10px;
		background-color: #409EFF;
		width: 5px;
		height: 20px;
		margin-left: 12px;
	}
	
	.qiun-title-text {
		font-size: 20px;
		color: #666666;
		margin-left: 8px;
		line-height: 20px;
		height: 20px;
		font-weight: bold;
	}
</style>