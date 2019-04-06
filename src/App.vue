<template>
  <div id="app">
      <nav>
        <router-link to="/">Home</router-link>
        <router-link to="/About">About</router-link>
      </nav>
      <router-view/>
  </div>
</template>

<script>
import Home from "./views/Home.vue";
import About from './views/About.vue';

export default {
  name: 'app',
  components:{
      Home,
      About
  }
}
</script>


<style lang="scss">
    body{
      background: #eee;
    }
</style>
