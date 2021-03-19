<template>
  <div id="app">
    <main-tar-bar></main-tar-bar>
    <router-view></router-view>
  </div>
</template>

<script>
import MainTarBar from "@/components/content/maintarbar/MainTarBar";
import NavBar from "@/components/common/navbar/NavBar";
export default {
  name: 'App',
  components: {
    NavBar,
    MainTarBar
  }
}
</script>

<style>
@import "assets/css/base.css";
</style>
