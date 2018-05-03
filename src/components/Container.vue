<template>
<div class="container-fluid text-center">    
  <div class="row content">
    <div class="col-sm-2 sidenav">
    I will be sidebar
    </div>

    <div class="col-sm-7 text-left"> 
      <router-view />      
    </div>

    <div class="col-sm-3 sidenav">
      I am sidebar for ads
    </div>
  </div>
</div>

</template>

<script>
export default {
  name: 'Container'

}
</script>

<style scoped>

</style>
