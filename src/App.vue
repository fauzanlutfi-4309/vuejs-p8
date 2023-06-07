<template>
  <Header />
  <Hero />
</template>

<script>
import Hero from './components/CompHero.vue'
import Header from './components/CompHeader.vue'
export default{
  name:'App',
  components:{
    Hero,
    Header,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
