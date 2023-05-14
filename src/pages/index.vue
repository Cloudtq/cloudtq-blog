<template>
    <div id="mainBox">
      <AuthorInfo></AuthorInfo>
      <LeftBackground></LeftBackground>
      <LeftBlackBox></LeftBlackBox>
      <LeftBottomInfo></LeftBottomInfo>
      <LeftMiddleInfo></LeftMiddleInfo>
      <LeftTopInfo></LeftTopInfo>
      <MiddleLogo></MiddleLogo>
      <RighrSwiper></RighrSwiper>
      <RightBackground></RightBackground>
      <RightInfo></RightInfo>
    </div>
  </template>
  
<script>
import AuthorInfo from '../components/AuthorInfo.vue';
import LeftBackground from '../components/LeftBackground.vue';
import LeftBlackBox from '../components/LeftBlackBox.vue';
import LeftBottomInfo from '../components/LeftBottomInfo.vue';
import LeftMiddleInfo from '../components/LeftMiddleInfo.vue';
import LeftTopInfo from '../components/LeftTopInfo.vue';
import MiddleLogo from '../components/MiddleLogo.vue';
import RighrSwiper from '../components/RighrSwiper.vue';
import RightBackground from '../components/RightBackground.vue';
import RightInfo from '../components/RightInfo.vue';

export default {
  name: 'index',
  components: {
    AuthorInfo,
    LeftBackground,
    LeftBlackBox,
    LeftBottomInfo,
    LeftMiddleInfo,
    LeftTopInfo,
    MiddleLogo,
    RighrSwiper,
    RightBackground,
    RightInfo
  }
}
</script>

<style lang="less" scoped>
@import './index.less';
</style>
  