<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                    <router-link class="text-white px-3" to="/">Top</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="text-white px-3" to="/favorite">favorite</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="text-white px-3" to="/discount">discount</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="text-white px-3" to="/map">map</router-link>
                </li>
                <li class="nav-item">
                    <img :src="image_src" class="img">
                </li>
                </ul>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
  data () {
    return {
      image_src: require('../../../static/bell.png') //
    }
  }
}
</script>
