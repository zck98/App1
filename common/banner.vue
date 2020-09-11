<template>
	<view>
		<swiper class="swiper" :indicator-dots="indicatorDots" :autoplay="autoplay" :interval="interval" :duration="duration" circular="true">
		    <swiper-item v-for="(item,index) in imgList" :key="index">
					<image :src="item.url"></image>
					<!-- <div>{{item.url}}</div> -->
		    </swiper-item>
		 </swiper>
	</view>
</template>

<script>
	export default{
		data(){
			return{
				 indicatorDots: true,
				 autoplay: true,
				 interval: 2500,
				 duration: 500,
				 imgList:[
					 {url:"https://ossweb-img.qq.com/upload/adw/image/20200910/d8d6694d71c3575ddfe21943e3c97f38.jpeg"},
					 {url:"https://ossweb-img.qq.com/upload/adw/image/20200910/7271845069f497329ac5d5efa006c578.jpeg"},
					 {url:"https://ossweb-img.qq.com/upload/adw/image/20200911/d0a43e3e004134ca72a326679ce197ff.jpeg"}
				 ]
			}
		},
		methods:{
			test(item,index){
				console.log(item.url,index)
			}
		}
	}
</script>

<style scoped>
</style>
