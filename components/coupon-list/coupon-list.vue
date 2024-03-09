<template>
	<view class="p-2">
		<scroll-view scroll-x="true" class="scroll-row">
			<view style="width: 310rpx; display: inline-flex;" class="flex text-white mr-3" 
			  v-for="i in 3" :key="i">
				<view class="flex flex-column align-center justify-center bg-hover-warning
				  px-3 py-2" style="border-right: 4rpx dashed;">
					<text>$200</text>
					<text class="font">满200可用</text>
				</view>
				<view style="width: 120rpx;" class="flex flex-column align-center justify-center bg-warning
				  font" hover-class="bg-hover-warning">
					领取
				</view>
			</view>
		</scroll-view>
	</view>
</template>

<script>
	export default {
		name:"coupon-list",
		data() {
			return {
				
			};
		}
	}
</script>

<style>

</style>