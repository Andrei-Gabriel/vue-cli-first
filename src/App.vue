<template>
  <div id="app">
    <primoProgetto/>
    <jumbotron/>
  </div>
</template>

<script>
import primoProgetto from './components/primoProgetto'
import jumbotron from './components/jumbotron'

export default {
  name: 'App',
  components: {
    primoProgetto,
    jumbotron
  }
}
</script>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-size: 100%;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  margin-top: 60px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
