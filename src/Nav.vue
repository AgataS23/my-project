<template>
  <div id="nav">
    <NavBanner/>
  </div>
</template>

<script>
import NavBanner from './components/NavBanner'

export default {
  name: 'Nav',
  components: {
    NavBanner
  }
}
</script>

<style>

#nav {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
