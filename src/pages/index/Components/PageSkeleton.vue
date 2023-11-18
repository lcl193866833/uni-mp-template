<template name="skeleton">
  <view class="sk-container">
    <view class="viewport" style="border: none">
      <view is="pages/index/components/CustomNavbar">
        <view
          class="navbar CustomNavbar--navbar data-v-ff0d84a2 CustomNavbar--data-v-ff0d84a2"
          style="padding-top: 20px; border: none"
        >
          <view
            class="flex CustomNavbar--flex items-center CustomNavbar--items-center h-64 CustomNavbar--h-64 pl-30 CustomNavbar--pl-30 pt-20 CustomNavbar--pt-20 data-v-ff0d84a2 CustomNavbar--data-v-ff0d84a2"
            style="border: none"
          >
            <image
              class="w-200 CustomNavbar--w-200 h-50 CustomNavbar--h-50 data-v-ff0d84a2 CustomNavbar--data-v-ff0d84a2 sk-image"
              style="border: none"
            ></image>
            <text
              class="logo-text CustomNavbar--logo-text data-v-ff0d84a2 CustomNavbar--data-v-ff0d84a2 sk-transparent sk-text-0-0000-51 sk-text"
              style="border: none"
              >新鲜 · 亲民 · 快捷</text
            >
          </view>
          <view
            class="search CustomNavbar--search data-v-ff0d84a2 CustomNavbar--data-v-ff0d84a2"
            style="border: none"
          >
            <text
              class="icon-search CustomNavbar--icon-search data-v-ff0d84a2 CustomNavbar--data-v-ff0d84a2 sk-transparent sk-text-14-2857-329 sk-text sk-pseudo sk-pseudo-circle"
              style="border: none"
              >搜索商品</text
            >
            <text
              class="icon-scan CustomNavbar--icon-scan data-v-ff0d84a2 CustomNavbar--data-v-ff0d84a2 sk-pseudo sk-pseudo-circle"
              style="border: none"
            ></text>
          </view>
        </view>
      </view>
      <scroll-view refresher-enabled="true" scroll-y="true" class="scroll-view" style="border: none">
        <view is="components/wSwiper/wSwiper">
          <view class="carousel wSwiper--carousel" style="border: none">
            <swiper
              circular="true"
              interval="3000"
              current="0"
              autoplay="false"
              style="border: none"
            ></swiper>
            <view class="indicator wSwiper--indicator" style="border: none">
              <text class="dot wSwiper--dot" style="border: none"></text>
              <text class="dot wSwiper--dot" style="border: none"></text>
              <text class="dot wSwiper--dot active wSwiper--active" style="border: none"></text>
              <text class="dot wSwiper--dot" style="border: none"></text>
              <text class="dot wSwiper--dot" style="border: none"></text>
            </view>
          </view>
        </view>
        <view is="pages/index/components/CategoryPanel">
          <view class="category CategoryPanel--category" style="border: none">
            <navigator
              class="category-item CategoryPanel--category-item"
              hover-class="none"
              style="border: none"
            >
              <image class="icon CategoryPanel--icon sk-image" style="border: none"></image>
              <text
                class="text CategoryPanel--text sk-transparent sk-text-14-2857-197 sk-text"
                style="border: none"
                >居家</text
              >
            </navigator>
            <navigator
              class="category-item CategoryPanel--category-item"
              hover-class="none"
              style="border: none"
            >
              <image class="icon CategoryPanel--icon sk-image" style="border: none"></image>
              <text
                class="text CategoryPanel--text sk-transparent sk-text-14-2857-807 sk-text"
                style="border: none"
                >锦鲤</text
              >
            </navigator>
            <navigator
              class="category-item CategoryPanel--category-item"
              hover-class="none"
              style="border: none"
            >
              <image class="icon CategoryPanel--icon sk-image" style="border: none"></image>
              <text
                class="text CategoryPanel--text sk-transparent sk-text-14-2857-576 sk-text"
                style="border: none"
                >服饰</text
              >
            </navigator>
            <navigator
              class="category-item CategoryPanel--category-item"
              hover-class="none"
              style="border: none"
            >
              <image class="icon CategoryPanel--icon sk-image" style="border: none"></image>
              <text
                class="text CategoryPanel--text sk-transparent sk-text-14-2857-756 sk-text"
                style="border: none"
                >母婴</text
              >
            </navigator>
            <navigator
              class="category-item CategoryPanel--category-item"
              hover-class="none"
              style="border: none"
            >
              <image class="icon CategoryPanel--icon sk-image" style="border: none"></image>
              <text
                class="text CategoryPanel--text sk-transparent sk-text-14-2857-538 sk-text"
                style="border: none"
                >个护</text
              >
            </navigator>
            <navigator
              class="category-item CategoryPanel--category-item"
              hover-class="none"
              style="border: none"
            >
              <image class="icon CategoryPanel--icon sk-image" style="border: none"></image>
              <text
                class="text CategoryPanel--text sk-transparent sk-text-14-2857-678 sk-text"
                style="border: none"
                >严选</text
              >
            </navigator>
            <navigator
              class="category-item CategoryPanel--category-item"
              hover-class="none"
              style="border: none"
            >
              <image class="icon CategoryPanel--icon sk-image" style="border: none"></image>
              <text
                class="text CategoryPanel--text sk-transparent sk-text-14-2857-247 sk-text"
                style="border: none"
                >数码</text
              >
            </navigator>
            <navigator
              class="category-item CategoryPanel--category-item"
              hover-class="none"
              style="border: none"
            >
              <image class="icon CategoryPanel--icon sk-image" style="border: none"></image>
              <text
                class="text CategoryPanel--text sk-transparent sk-text-14-2857-317 sk-text"
                style="border: none"
                >运动</text
              >
            </navigator>
            <navigator
              class="category-item CategoryPanel--category-item"
              hover-class="none"
              style="border: none"
            >
              <image class="icon CategoryPanel--icon sk-image" style="border: none"></image>
              <text
                class="text CategoryPanel--text sk-transparent sk-text-14-2857-72 sk-text"
                style="border: none"
                >杂项</text
              >
            </navigator>
            <navigator
              class="category-item CategoryPanel--category-item"
              hover-class="none"
              style="border: none"
            >
              <image class="icon CategoryPanel--icon sk-image" style="border: none"></image>
              <text
                class="text CategoryPanel--text sk-transparent sk-text-14-2857-545 sk-text"
                style="border: none"
                >品牌</text
              >
            </navigator>
          </view>
        </view>
        <view is="pages/index/components/HotPannel">
          <view class="panel HotPannel--panel hot HotPannel--hot" style="border: none">
            <view class="item HotPannel--item" style="border: none">
              <view class="title HotPannel--title" style="border: none">
                <text
                  class="title-text HotPannel--title-text sk-transparent sk-text-14-2857-385 sk-text"
                  style="border: none"
                  >特惠推荐</text
                >
                <text
                  class="title-desc HotPannel--title-desc sk-transparent sk-text-14-2857-514 sk-text"
                  style="border: none"
                  >精选全攻略</text
                >
              </view>
              <navigator class="cards HotPannel--cards" hover-class="none" style="border: none">
                <image class="image HotPannel--image sk-image" mode="aspectFit" style="border: none"></image>
                <image class="image HotPannel--image sk-image" mode="aspectFit" style="border: none"></image>
              </navigator>
            </view>
            <view class="item HotPannel--item" style="border: none">
              <view class="title HotPannel--title" style="border: none">
                <text
                  class="title-text HotPannel--title-text sk-transparent sk-text-14-2857-667 sk-text"
                  style="border: none"
                  >爆款推荐</text
                >
                <text
                  class="title-desc HotPannel--title-desc sk-transparent sk-text-14-2857-720 sk-text"
                  style="border: none"
                  >最受欢迎</text
                >
              </view>
              <navigator class="cards HotPannel--cards" hover-class="none" style="border: none">
                <image class="image HotPannel--image sk-image" mode="aspectFit" style="border: none"></image>
                <image class="image HotPannel--image sk-image" mode="aspectFit" style="border: none"></image>
              </navigator>
            </view>
            <view class="item HotPannel--item" style="border: none">
              <view class="title HotPannel--title" style="border: none">
                <text
                  class="title-text HotPannel--title-text sk-transparent sk-text-14-2857-245 sk-text"
                  style="border: none"
                  >一站买全</text
                >
                <text
                  class="title-desc HotPannel--title-desc sk-transparent sk-text-14-2857-815 sk-text"
                  style="border: none"
                  >精心优选</text
                >
              </view>
              <navigator class="cards HotPannel--cards" hover-class="none" style="border: none">
                <image class="image HotPannel--image sk-image" mode="aspectFit" style="border: none"></image>
                <image class="image HotPannel--image sk-image" mode="aspectFit" style="border: none"></image>
              </navigator>
            </view>
            <view class="item HotPannel--item" style="border: none">
              <view class="title HotPannel--title" style="border: none">
                <text
                  class="title-text HotPannel--title-text sk-transparent sk-text-14-2857-940 sk-text"
                  style="border: none"
                  >新鲜好物</text
                >
                <text
                  class="title-desc HotPannel--title-desc sk-transparent sk-text-14-2857-102 sk-text"
                  style="border: none"
                  >生活加分项</text
                >
              </view>
              <navigator class="cards HotPannel--cards" hover-class="none" style="border: none">
                <image class="image HotPannel--image sk-image" mode="aspectFit" style="border: none"></image>
                <image class="image HotPannel--image sk-image" mode="aspectFit" style="border: none"></image>
              </navigator>
            </view>
          </view>
        </view>
      </scroll-view>
    </view>
  </view>
</template>
<style lang="scss">
.sk-transparent {
  color: transparent !important;
}
.sk-text-0-0000-51 {
  background-image: linear-gradient(transparent 0%, #eeeeee 0%, #eeeeee 100%, transparent 0%) !important;
  background-size: 100% 25.7813rpx;
  position: relative !important;
}
.sk-text {
  background-origin: content-box !important;
  background-clip: content-box !important;
  background-color: transparent !important;
  color: transparent !important;
  background-repeat: repeat-y !important;
}
.sk-text-14-2857-329 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 36.0938rpx;
  position: relative !important;
}
.sk-text-14-2857-197 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 36.0938rpx;
  position: relative !important;
}
.sk-text-14-2857-807 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 36.0938rpx;
  position: relative !important;
}
.sk-text-14-2857-576 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 36.0938rpx;
  position: relative !important;
}
.sk-text-14-2857-756 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 36.0938rpx;
  position: relative !important;
}
.sk-text-14-2857-538 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 36.0938rpx;
  position: relative !important;
}
.sk-text-14-2857-678 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 36.0938rpx;
  position: relative !important;
}
.sk-text-14-2857-247 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 36.0938rpx;
  position: relative !important;
}
.sk-text-14-2857-317 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 36.0938rpx;
  position: relative !important;
}
.sk-text-14-2857-72 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 36.0938rpx;
  position: relative !important;
}
.sk-text-14-2857-545 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 36.0938rpx;
  position: relative !important;
}
.sk-text-14-2857-385 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 42.6563rpx;
  position: relative !important;
}
.sk-text-14-2857-514 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 32.8125rpx;
  position: relative !important;
}
.sk-text-14-2857-667 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 42.6563rpx;
  position: relative !important;
}
.sk-text-14-2857-720 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 32.8125rpx;
  position: relative !important;
}
.sk-text-14-2857-245 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 42.6563rpx;
  position: relative !important;
}
.sk-text-14-2857-815 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 32.8125rpx;
  position: relative !important;
}
.sk-text-14-2857-940 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 42.6563rpx;
  position: relative !important;
}
.sk-text-14-2857-102 {
  background-image: linear-gradient(
    transparent 14.2857%,
    #eeeeee 0%,
    #eeeeee 85.7143%,
    transparent 0%
  ) !important;
  background-size: 100% 32.8125rpx;
  position: relative !important;
}
.sk-image {
  background: #efefef !important;
}
.sk-pseudo::before,
.sk-pseudo::after {
  background: #efefef !important;
  background-image: none !important;
  color: transparent !important;
  border-color: transparent !important;
}
.sk-pseudo-rect::before,
.sk-pseudo-rect::after {
  border-radius: 0 !important;
}
.sk-pseudo-circle::before,
.sk-pseudo-circle::after {
  border-radius: 50% !important;
}
.sk-container {
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: hidden;
  background-color: transparent;
}
</style>
