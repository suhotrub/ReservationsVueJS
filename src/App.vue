<template>
  <reservations swipeable/>
</template>

<script>
import Reservations from './components/Reservations'

export default {
  name: 'App',
  components: {
      Reservations
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
