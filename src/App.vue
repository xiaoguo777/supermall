<template>
  <div id="app">
      <router-view/>
      <MainTarBar/>
  </div>
</template>

<script>
import MainTarBar from 'components/content/maintarbar/MainTarBar'

export default {
   components:{
     MainTarBar
   }
}
</script>


<style>
  /*css 引入方式*/
  @import "assets/css/base.css";
</style>
