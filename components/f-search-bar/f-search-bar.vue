<template>
	<view class="p-2">
		<view style="background-color: #f5f5f5;color: #928E8A; font-size: 30rpx;" 
		  class="flex justify-center align-center py-1 rounded-circle"
			@click="open">
			<uni-icons color="#928E8A" type="search" size="15"></uni-icons>
			<text class="ml-2">{{placeholder}}</text>
		</view>
	</view>
</template>

<script>
	export default {
		name: "f-search-bar",
		props: {
			placeholder: String,
			default: '请输入搜索内容'
		},
		data() {
			return {

			};
		},
		methods: {
			open() {
				uni.navigateTo({
					url: '/pages/search/search'
				});
			}
		}
	}
</script>

<style>

</style>