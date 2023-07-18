<template>
	<view class="content">
		<image class="logo" src="/static/logo.png"></image>
		<view class="text-area">
			<text class="title">{{title}}</text>
		</view>

    <view class="">
		<u-search placeholder="日照香炉生紫烟" v-model="keyword"></u-search>
    </view>
	<u-button type="success" :plain="false" :hairline="true" text="细边"></u-button>
	</view>
</template>
<!-- <template>
	
</template> -->

<script>
	export default {
		data() {
			return {
				title: 'Hello',
				keyword: '遥看瀑布挂前川'
			}
		},
		onLoad() {
			console.log(uni.$u.config.v);

		},
		methods: {

		}
	}
</script>

<style lang="scss">
  .text-area{
	  .title{
		  color: red;
	  }
  }
</style>
