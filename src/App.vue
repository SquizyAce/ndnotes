<template>
  <div id="app">
    <div class="header">
      <img src="./assets/logo.svg" alt="">
      <cs-button icon="login">Вход</cs-button>
    </div>
    <div class="main">
      <div class="main__descBlock">
        <span>Мои <br>заметки</span>
        <span>Не забывай о важном,<br> храни его в облаке.</span>
      </div>
      <pageLogo></pageLogo>
    </div>
  </div>
</template>

<script>
import csButton from './components/cs-button.vue'
import pageLogo from './assets/pageLogo.vue'

export default {
  components: { csButton, pageLogo },
  name: 'App',
  data () {
    return {

    }
  }
}
</script>
