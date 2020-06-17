<template>
	<view class="content">
		<t-city/>
	</view>
</template>

<script>
	import TCity from '@/components/t-city.vue';
	export default {
		components:{
			't-city':TCity
		},
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content{
		width: 100%;
	}

</style>
