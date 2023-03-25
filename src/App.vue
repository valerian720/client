<template>
  <div id="app">
    <BlockGame />
  </div>
</template>
<script>
// importing the BlockGame component into the app file
import BlockGame from './components/BlockGame.vue'
export default {
  name: 'app',
  components: {
    BlockGame
  }
}
</script>
<style>
</style>
