<template>
	<view class="page dataease-main">
		<uni-list>
                
            <uni-list-item title="2021年全国GDP数据1"  showArrow thumb="../../../static/folder-close.png" thumb-size="base" rightText="1" />
            <uni-list-item title="2021年全国GDP数据1"  showArrow thumb="../../../static/folder-close.png" thumb-size="base" rightText="2" />
            <uni-list-item title="2021年全国GDP数据1"  showArrow thumb="../../../static/folder-close.png" thumb-size="base" rightText="3" />
            <uni-list-item title="2021年全国GDP数据1"  showArrow thumb="../../../static/folder-close.png" thumb-size="base" rightText="4" />
            <uni-list-item title="2021年全国GDP数据1"  showArrow thumb="../../../static/folder-close.png" thumb-size="base" rightText="3" />
            <uni-list-item title="2021年全国GDP数据1"  showArrow thumb="../../../static/folder-close.png" thumb-size="base" rightText="2" />
            <uni-list-item title="2021年全国GDP数据1"  showArrow thumb="../../../static/folder-close.png" thumb-size="base" rightText="4" />
            
        </uni-list>
	</view>
</template>

<script>
export default {
	data() {
		return {
			showSwiper: false,
			imgUrls: [
				'https://vkceyugu.cdn.bspapp.com/VKCEYUGU-dc-site/b4b60b10-5168-11eb-bd01-97bc1429a9ff.jpg',
				'https://vkceyugu.cdn.bspapp.com/VKCEYUGU-dc-site/b1dcfa70-5168-11eb-bd01-97bc1429a9ff.jpg'
			]
		};
	},
	/**
	 * 当 searchInput 配置 disabled 为 true 时触发
	 */
	onNavigationBarSearchInputClicked(e) {
		console.log('事件执行了')
		/* uni.navigateTo({
			url: '/pages/template/nav-search-input/detail/detail'
		}); */
	},
	/**
	 *  点击导航栏 buttons 时触发
	 */
	/* onNavigationBarButtonTap() {
		uni.showModal({
			title: '提示',
			content: '用户点击了功能按钮，这里仅做展示。',
			success: res => {
				if (res.confirm) {
					console.log('用户点击了确定');
				}
			}
		});
	} */
};
</script>

<style>
image,
swiper,
.img-view {
	width: 750rpx;
	width: 100%;
	height: 500rpx;
}
.page-section-title {
	margin-top: 50rpx;
}

.dataease-main {
    
    width: 100%;
    position: absolute;
    top: 40px;
    height: calc(100vh - 80px);
    margin: 5px 10px;
}

</style>
