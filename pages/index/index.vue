<template>
	<view>
		<image src="../../static/lunbo.jpeg" mode="widthFix"></image>
		<view class="center padding20" style="background-color: #FFFFFF;">
			<view class="border padding20" style="width: 345rpx; height: 150rpx; background-color: red; color: #FFFFFF;">
				<view>
					商家入驻
				</view>
				<view class="border center2" style="width: 150rpx; border-radius: 50rpx; font-size: 30rpx; margin-top: 10rpx;">
					开始入驻
				</view>
			</view>
			<view class="border padding20" style="width: 345rpx; height: 150rpx; background-color: red; margin-left: auto; color: #FFFFFF;">
				<view>
					商家入驻
				</view>
				<view class="border center2" style="width: 150rpx; border-radius: 50rpx; font-size: 30rpx; margin-top: 10rpx;">
					开始入驻
				</view>
			</view>
		</view>
		<view class="padding20" style="background-color: #FFFFFF;">
			<view class="" style="border-left: 20rpx solid red; color: red; padding-left: 20rpx;">本地商家</view>
			<scroll-view class="" scroll-x="true" style="width: 100%; overflow: hidden; white-space: nowrap;">
				<view class="center">
					<view class="" v-for="item in dataList" key="index">
						<image src="../../static/logo.jpg" mode="aspectFill" style="width: 100rpx; height: 100rpx;" />
						<view class="">{{ item.name }}</view>
					</view>
				</view>
			</scroll-view>
		</view>
		<view class="padding20 center" v-for="item in 10"style="background-color: #FFFFFF;">
			<image class="logo" src="../../static/logo.jpg" mode=""></image>
			<view class="" style="margin-left: 20rpx;">
				<view class="">
					<view class="center">
						<view class="padding20" style="background-color: red; color: #FFFFFF; padding: 5rpx;">求职</view>
						<view style="margin-left: 20rpx;">深蓝</view>
						<view style="margin-left: auto;">详情</view>
					</view>
					<view class="center">
						<view class="border" v-for="item in 3" style="margin-left: 20rpx;">标签</view>
					</view>
					<view class="">aaaaaaaaaaaaaaaaaaaaaaaaaaaaa</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: "Hello World",
				dataList: [
					{url: "/static/logo.jpg", name: "专业钻井"},
					{url: "/static/logo.jpg", name: "专业钻井"},
					{url: "/static/logo.jpg", name: "专业钻井"},
					{url: "/static/logo.jpg", name: "专业钻井"},
					{url: "/static/logo.jpg", name: "专业钻井"},
					{url: "/static/logo.jpg", name: "专业钻井"},
					{url: "/static/logo.jpg", name: "专业钻井"}
				],
			}
		},
		onLoad() {
			
		},
		methods: {
			
		}
	}
</script>

<style>
	page{
		background-color: #F2F2F2;
	}
</style>
