<template>
	<view>
		<!-- <view class="intro">本项目已包含uni ui组件，无需import和注册，可直接使用。在代码区键入字母u，即可通过代码助手列出所有可用组件。光标置于组件名称处按F1，即可查看组件文档。</view>
		<text class="intro">详见：</text>
		<uni-card title="标题文字" thumbnail="" extra="额外信息" note="Tips">
			内容主体，可自定义内容及样式
		</uni-card>
		<uni-grid :column="3">
			<uni-grid-item>1</uni-grid-item>
			<uni-grid-item>2</uni-grid-item>
		</uni-grid>
		<uni-link :href="href" :text="href"></uni-link> -->
		<Banner></Banner>
	</view>
</template>

<script>
	import Banner from "../../common/banner.vue"
	export default {
		data() {
			return {
				// url: 'https://uniapp.dcloud.io/component/README?id=uniui'
			}
		},
		components:{
			Banner
		},
		methods: {
		
		}
	}
</script>

<style>
	
</style>
