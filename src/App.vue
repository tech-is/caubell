<template>
  <div id="app">
    <myheader></myheader>
    <router-view/>
  </div>
</template>

<script>
import myheader from './components/component/myheader'
export default {
  name: 'App',
  components: {
    myheader
  }
}
</script>

<style>
@import "assets/css/user.css";
</style>
