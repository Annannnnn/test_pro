<!--
 * @Author: jiaojiao.zhong
 * @Date: 2021-07-10 16:06:09
 * @LastEditors: jiaojiao.zhong
 * @LastEditTime: 2021-07-12 13:58:11
 * @Description: 
-->
<template>
 <h1>Hello world!</h1>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
