<template>
  <view class="index">
    <view class="w-300rpx h-300rpx pl-30rpx ml-30rpx bg-gray  text-red">
      <text>{{ msg }}</text>
    </view>
  </view>
</template>

<script>
import { ref } from "vue";
import "./index.scss";

export default {
  setup() {
    const msg = ref("Hello world");
    return {
      msg
    };
  }
};
</script>
