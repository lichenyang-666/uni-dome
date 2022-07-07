<template>
	<view class="container">
		
		<view class="intro">这个就是一个新的测试项目</view>
		<text class="a">详见：</text>
		<uni-link :href="href" :text="href"></uni-link>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				href: 'https://uniapp.dcloud.io/component/README?id=uniui'
			}
		},
		methods: {

		}
	}
</script>

<style lang="scss">
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
		.a {
			background-color: #6e6e6e;
		}
	}
</style>
