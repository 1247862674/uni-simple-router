<template>
	<view>
		<h1>组件1</h1>
		<comChild></comChild>
	</view>
</template>

<script>
	import comChild from '../comChild/comChild.vue'
	export default {
		components:{
			comChild
		},
		data() {
			return {
				
			}
		},
		beforeCreate(){
			console.log('index--beforeCreate----beforeCreate')
		},
		created(){
			console.log('index--created----created')
		},
		mounted(){
			console.log('index--mounted----mounted')
		},
		onLoad() {
			console.log('index-child-----onload')
		},
		onShow() {
			console.log('index-child-----onShow');
		},
		methods: {
			
		}
	}
</script>

<style>

</style>
