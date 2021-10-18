<template>
	<view>
		<view class="center padding20" style="background-color: red; color: #FFFFFF;">
			<image class="logo" src="../../static/logo.png" mode="" />
			<view class="" style="margin-left: 20rpx;">
				<view class="">典韦</view>
				<view class="">UID: 111111</view>
				<view class="">未绑定手机号</view>
			</view>
		</view>
		<view class="center2 padding20" style="background-color: #FFFFFF; margin-bottom: 20rpx;">
			<view class="center2" style="width: 200rpx;">
				<view class="">
					<view class="center2" style="color: red;">0</view>
					<view class="center2">积分</view>
				</view>
			</view>
			<view class="center2" style="width: 200rpx;">
				<view class="">
					<view class="center2" style="color: red;">0.00</view>
					<view class="center2">余额</view>
				</view>
			</view>
		</view>
		<view class="padding20 center" style="background-color: #FFFFFF; margin-top: 2rpx;" v-for="item in 10">
			<view class="">我的发布</view>
			<view class="" style="margin-left: auto;">></view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
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
