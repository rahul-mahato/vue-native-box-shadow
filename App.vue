<template>
  <view class="container">
    <view class="shadow-box" :style="styles.shadowBox" />
  </view>
</template>
<script>
import { StyleSheet } from 'react-native';
export default {
  data: function () {
    return {
      styles: new StyleSheet.create({
        shadowBox: {
          elevation: 60,
          shadowOffset: { width: 2, height: 2 },
          shadowColor: '#000000',
          shadowOpacity: 0.8,
          height: 500,
          backgroundColor: '#000',
          width: 200,
          shadowRadius: 50,
        },
      }),
    };
  },
};
</script>
<style>
.container {
  flex: 1;
}

.camera-container {
  height: 500;
  width: 500;
}
.text-color-primary {
  color: blue;
}
</style>
i
