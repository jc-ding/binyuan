<template>
	<view>
		<image src="../../static/lunbo.jpeg" mode="widthFix" style="width: 100%;"></image>
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
			<view class="" style="border-left: 10rpx solid red; color: red; padding-left: 20rpx;">本地商家</view>
			<scroll-view class="" scroll-x="true" style="width: 100%; overflow: hidden; white-space: nowrap; margin-top: 20rpx;">
				<view class="center">
					<view class="" v-for="item in dataList" key="index" @click="toInfo">
						<image src="../../static/logo.png" mode="aspectFill" style="width: 100rpx; height: 100rpx;" />
						<view class="" style="color: #515151;">{{ item.name }}</view>
					</view>
				</view>
			</scroll-view>
		</view>
		<view class="padding20 center" v-for="item in 10"style="background-color: #FFFFFF; width: 100%; align-items: inherit" @click="toInfo">
			<image class="logo" src="../../static/logo.png" mode=""></image>
			<view class="" style="margin-left: 20rpx; width: 590rpx;">
				<view class="center">
					<view class="padding20" style="background-color: red; color: #FFFFFF; padding: 5rpx;">求职</view>
					<view style="margin-left: 20rpx; color: #515151;">深蓝</view>
					<view style="margin-left: auto; color: #8a8a8a;">详情</view>
				</view>
				<view class="center" style="margin-top: 20rpx;">
					<view class="border padding20" v-for="item in 3" style="margin-left: 20rpx; background-color: #F2F2F2; padding: 5rpx; color: #8a8a8a;">标签</view>
				</view>
				<view class="text2 padding20" style="margin-top: 20rpx; background-color: #F2F2F2; color: #515151;">aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</view>
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
					{url: "/static/logo.png", name: "专业钻井"},
					{url: "/static/logo.png", name: "专业钻井"},
					{url: "/static/logo.png", name: "专业钻井"},
					{url: "/static/logo.png", name: "专业钻井"},
					{url: "/static/logo.png", name: "专业钻井"},
					{url: "/static/logo.png", name: "专业钻井"},
					{url: "/static/logo.png", name: "专业钻井"}
				],
			}
		},
		onLoad() {
			
		},
		methods: {
			toInfo(){
				let id = '1';
				uni.navigateTo({
					url: `/pages/info/info?id=${id}`
				})
			}
		}
	}
</script>

<style>
	page{
		background-color: #F2F2F2;
	}
</style>
