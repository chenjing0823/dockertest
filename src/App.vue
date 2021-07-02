<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">主页测试</router-link> |
      <router-link to="/about">关于测试</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="stylus">
#app
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  margin-top 60px
</style>
