<template>
	<view>
		{{ msg }}
		<button type="primary" @click="test">Event</button>
	</view>
</template>

<script>
	export default {
		props: {
			msg: {
				type: String,
				default: ''
			}
		},
		data() {
			return {
				
			};
		},
		methods: {
			test() {
				// this.$emit('testShowName', {
				// 	name: 'Name'
				// })
				uni.$emit('testEmit', {
					name: 'lucy'
				})
			}
		}
	}
</script>

<style lang="scss">

</style>
