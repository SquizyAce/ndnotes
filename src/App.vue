<template>
  <div id="app">
    <div class="header">
      <img src="./assets/logo.png" alt="">
      <cs-button icon="login">Вход</cs-button>
    </div>
  </div>
</template>

<script>
import csButton from './components/cs-button.vue'
// import HelloWorld from './components/HelloWorld.vue'

export default {
  components: { csButton },
  name: 'App',
  data () {
    return {

    }
  }
}
</script>
