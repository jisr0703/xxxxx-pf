<template>
  <CommonHeader/>
  <CommonNav/>
  <PortfolioMain/>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <CommonFooter/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import CommonHeader from './components/common/CommonHeader.vue'
import CommonNav from './components/common/CommonNav.vue'
import CommonFooter from './components/common/CommonFooter.vue'
import PortfolioMain from './components/PortfolioMain.vue'
import '@/styles/global.css'

export default {
  name: 'App',
  components: {
    HelloWorld,
    CommonHeader,
    CommonNav,
    CommonFooter,
    PortfolioMain
  }
}
</script>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  /* -webkit-font-smoothing: antialiased; */
  /* -moz-osx-font-smoothing: grayscale; */
  /* text-align: center; */
  /* color: #2c3e50; */
  margin: 0;
}
</style>
