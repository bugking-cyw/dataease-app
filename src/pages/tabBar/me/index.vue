<template>
    <view>
        <view>
            <uni-card :is-shadow="true" >
                <view class="uni-flex uni-row">
                    <view class="text uni-flex" style="width: 200rpx;height: 220rpx;-webkit-justify-content: center;justify-content: center;-webkit-align-items: center;align-items: center;">
                        <image src="../../../static/logo.png" style="width: 150rpx;height: 150rpx;"></image>
                    </view>
                    <view class="uni-flex uni-column" style="-webkit-flex: 1;flex: 1;">
                        <view class="text" style="height: 90rpx;text-align: left;padding-left: 20rpx;padding-top: 40rpx; front-size: 25rpx;">
                            陈亚文
                        </view>
                        <view class="uni-flex uni-row" style="padding-left: 20rpx;">
                            <view class="text" style="-webkit-flex: 1;flex: 1;">管理员</view>
                            <view class="text" style="-webkit-flex: 1;flex: 1;">更多信息</view>
                        </view>
                    </view>
                </view>
            </uni-card>
        </view>

        <view>
            <uni-list>
                
                <uni-list-item title="语言"  showArrow thumb="../../../static/folder-close.png" thumb-size="base" rightText="简体中文" />
                <uni-list-item title="关于"  showArrow thumb="../../../static/folder-close.png" thumb-size="base" rightText="系统信息" />
            </uni-list>
        </view>

        <view>
            <button type="default" @click="">注销</button>
        </view>
    </view>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>