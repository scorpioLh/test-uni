<template>
	<view>
		<swiper :indicator-dots="true" :autoplay="true" :interval="3000" :duration="1000">
			<swiper-item>
				<view class="swiper-item">
					<image scaleToFill src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/images/shuijiao.jpg" mode=""></image>
				</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item">
					<image src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/images/shuijiao.jpg" mode=""></image>
				</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item">
					<image src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/images/shuijiao.jpg" mode=""></image>
				</view>
			</swiper-item>
		</swiper>
	</view>
</template>

<script>
	export default {
		data() {
			return {
			}
		},
		onLoad() {
			console.log('onLoad')
		},
		onReady() {
			console.log('onReady')
		},
		onShow() {
			console.log('onShow')
		},
		onHide() {
			console.log('onHide')
		},
		onTabItemTap() {
			console.log('onTabItemTap')
		}
	}
</script>

<style lang="scss">

</style>
