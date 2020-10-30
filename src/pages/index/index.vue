<template>
  <view class="index">
    <view class="photo-list" v-for="item in [0, 1, 2, 3, 4, 5 ,6]" :key="item">
      <view class="photo-item">
        <view class="img-wrap">
          <image class="img" src="https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/947decaaef3147b9ad7728105cc48798~tplv-k3u1fbpfcp-watermark.image" alt=""></image>
        </view>
        <view class="description">
          这是一段描述文字，可以很长很长很长的，至少两行吧
        </view>
      </view>
    </view>
  </view>
</template>

<script>
import { ref } from 'vue'
import './index.scss'

export default {
  setup () {
    const msg = ref('Hello world')
    return {
      msg
    }
  }
}
</script>
