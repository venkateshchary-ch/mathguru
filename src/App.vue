<template>
  <div v-if="isMobile"><HomePageMobile msg="Welcome to Your Vue.js App"/></div>
  <div v-else><HomePage msg="Welcome to Your Vue.js App"/></div>

</template>

<script>
import HomePage from './components/HomePage.vue';
import HomePageMobile from './components/HomePageMobile.vue';

export default {
  name: 'App',
  components: {
    HomePage,
    HomePageMobile
  },
  data() {
    return {
      isMobile: window.innerWidth < 768
    }
  },
  mounted() {
    // Update isMobile when window is resized
    window.addEventListener('resize', this.handleResize)
  },
  beforeUnmount() {
    window.removeEventListener('resize', this.handleResize)
  },
  methods: {
    handleResize() {
      this.isMobile = window.innerWidth < 768
    }
  }
}
</script>

<!-- <style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style> -->
