<template>
  <div>
    <h1>account组件</h1>
    <router-link to="/account/login">登录</router-link>
    <router-link to="/account/register">注册</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  
}
</script>

<style>
  /* 普通的style只支持普通的样式  如果要用scss 或者less  需要给style元素设置lang属性  
  lang="scss" */
</style>