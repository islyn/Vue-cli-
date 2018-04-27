<template>
    <div>
      <p>这是个人中心</p>
      <!--路由链接，相当于"<a></a>"-->
      <router-link to="/userCenter/userInfo">用户信息</router-link>
      <!--点击路由链接，内容显示的位置-->
      <router-view/>
    </div>
</template>

<script>
    export default {
        name: "userCenter"
    }
</script>

<style scoped>
  p{
    display: block;
    background: #d6e9c6;
  }
</style>
