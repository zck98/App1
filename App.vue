<script>
export default {
	onLaunch: function() {
		console.log('App Launch');
		// if(process.env.NODE_ENV === 'development'){
		//     alert('开发环境')
		// }else{
		//     alert('生产环境')
		// }
	},
	onShow: function() {
		console.log('App Show');
	},
	onHide: function() {
		console.log('App Hide');
	}
};
</script>

<style>
/* 解决头条小程序组件内引入字体不生效的问题 */
/* #ifdef MP-TOUTIAO */
@font-face {
	font-family: uniicons;
	src: url('/static/uni.ttf');
}
/* #endif */
</style>
