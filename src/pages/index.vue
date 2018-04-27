<template>
  <!--组件外层只能有一个div-->
  <div>
    <p>{{msg}}</p>
  </div>
</template>

<script>
    export default {
        name: "index",
        data(){
          return{
            msg:'这是首页'
          }
        }
    }
</script>

<style scoped>
  p{
    display: block;
    background: #ffe87c;
  }
</style>
