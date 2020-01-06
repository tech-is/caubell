<template>
  <div id="map">
    <myheader></myheader>
    <router-view/>
    <button class="btn btn-primary">test5</button>
  </div>
</template>

<script>
import myheader from './components/component/myheader'
export default {
  name: 'map',
  components: {
    myheader
  }  

}
</script>

<style>
#map {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>