<template>
  <view>
    <web-view src="/static/hybrid/index.html"></web-view>
  </view>
</template>

<script>
export default {
  data() {
    return {}
  },
  onLoad() {},
  methods: {
    rightClick() {
      console.log('rightClick')
    },
    leftClick() {
      console.log('leftClick')
    },
  },
}
</script>

<style></style>
