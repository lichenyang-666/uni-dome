<template>
	<view class="container">
		
		<view class="intro">本项目已包含uni ui组件，无需import和注册，可直接使用。在代码区键入字母u，即可通过代码助手列出所有可用组件。光标置于组件名称处按F1，即可查看组件文档。</view>
		<u-button>测试</u-button>
		<text class="intro">详见：</text>
		<view class="uni-padding-wrap uni-common-mt">
			<u-button >默认按钮</u-button>
			<u-button type="primary">主要按钮</u-button>
			<u-button type="success">成功按钮</u-button>
			<u-button type="info">信息按钮</u-button>
			<u-button type="warning">警告按钮</u-button>
			<u-button type="error">危险按钮</u-button>
			<u-button shape="square" type="primary">乌啼</u-button>
			<u-button :ripple="true" ripple-bg-color="#909399">之约</u-button>
		</view>
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

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
