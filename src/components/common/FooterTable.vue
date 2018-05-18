<template>
  <div>
    <h3><u>{{footerTableHeading}}</u></h3>
    <br><p class="text-muted"><slot name="footerTableContent"></slot></p>
    
  </div>
</template>

<script>
export default {
  name: 'FooterTable',
  props:['footerTableHeading'],
}
</script>

<style scopped>
.footer {
  background-color: #333333;
  color: #fff;
  padding: 5px;
  margin-top: 100px;
}
u {
  text-decoration-color:#0FBE7C
}
</style>


