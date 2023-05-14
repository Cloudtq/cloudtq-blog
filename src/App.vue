<template>
  <div>
    <index></index>
  </div>
</template>

<script>
import index from './pages/index.vue';

export default {
  name: 'App',
  components: {
    index
  }
}
</script>

<style lang="less" scoped>
@import './App.less';
</style>
