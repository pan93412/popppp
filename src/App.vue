<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Leaderboard />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Leaderboard from './components/Leaderboard.vue'

export default defineComponent({
  name: 'App',
  components: {
    Leaderboard
  }
})
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
