<template>
	<view class="content">
		<!-- 将插件随便放一个位置 -->
		<sa-hover-menu></sa-hover-menu>
		
		<!-- 填充内容 -->
		<image class="logo" src="/static/logo.png"></image>
		<!-- <view class="text-area">
			<text class="title">{{title}}</text>
		</view> -->
		<view class="full-box">
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
			<view>充数</view>
		</view>
	</view>
</template>

<script>
	import saHoverMenu from '../../components/sa-hover-menu/sa-hover-menu.vue';
	export default {
		components: {
			saHoverMenu
		},
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		background-color: #eee;
	}

	.logo {
		height: 100rpx;
		width: 100rpx;
		margin-top: 100rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
	
	.full-box{line-height: 30px;}
</style>
