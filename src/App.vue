<template>
  <div id="app">
    <router-view></router-view>
    <div @click="_alert()">{{msg}}</div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data(){
   return {
   
   }
  },
  methods:{
    
  }
}
</script>

<style lang="stylus" scoped>
#app
  backgroud:red
  color:blue
</style>
