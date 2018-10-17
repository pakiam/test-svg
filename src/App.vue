<template>
  <div id="app">
    <img src="./assets/logo.png">
    <svg class="icon">
        <use v-bind="{'xlink:href': `/sprite.svg#${icon}`}"></use>
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
      icon: 'organic'
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
