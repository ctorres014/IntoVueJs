<template lang="pug">
  #app
   station
</template>

<script>
import Station from './components/Station.vue'

export default {
  name: 'app',
  components: {
    Station
  }
}
</script>

<style lang="scss">
  @import './assets/scss/main.scss';

</style>
