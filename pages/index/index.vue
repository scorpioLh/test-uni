<template>
	<view class="content">
		<!-- <test :msg="msg" @testShowName="testEvent" /> -->
		<text>我是首页</text>
		<view>{{ 'abc'.indexOf('ab') === -1 ? 'yes' : 'no' }}</view>
		<image src="../../static/logo.png" mode=""></image>
	</view>
</template>

<script>
	import test from '../../components/test.vue'
	
	export default {
		components: {
			test
		},
		data() {
			return {
				msg: 'I am test'
			}
		},
		onLoad() {
			// uni.$once('testEmit', (e) => {
			// 	console.log(e)
			// })
		},
		methods: {
			// testEvent(e) {
			// 	console.log(e)
			// }
		}
	}
</script>

<style>
</style>
