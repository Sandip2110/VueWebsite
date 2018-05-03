<template>
  <div class="hello">
    <h1>Simple Vue Website</h1>
    <img src="https://www.wonderplugin.com/videos/demo-image0.jpg" alt="banner img">
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style scoped>
img {
  max-width: 100%;
}
</style>
