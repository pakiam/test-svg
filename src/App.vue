<template>
  <div id="app">
    <img src="./assets/logo.png">
    <svg class="icon">
        <use xlink:href="sprite.svg#organic"></use>
    </svg>
    <router-view/>
  </div>
</template>

<script>
// import symbolData from './assets/icons/organic.svg'

export default {
  name: 'App',
  data () {
    return {
    //   symbolData
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
