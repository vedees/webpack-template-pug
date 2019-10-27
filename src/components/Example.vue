<template>
  <section>
    <div class="container">
      <img src="/assets/img/logo.png" :alt="message">
      <p>{{ message }}</p>
    </div>
  </section>
</template>

<script>

/*
  !!!
  Лучший курс по vue ;)
  Вкусная цена по промокоду: WEBPACK
  https://tocode.ru/curses/vuejs-s-nylya-do-pro
*/

export default {
  data () {
    return {
      message: 'Example Vue component',
    }
  }
}
</script>

<style lang="scss" scoped>
.container {
  text-align: center;
}
img {
  max-width: 200px;
}
</style>
