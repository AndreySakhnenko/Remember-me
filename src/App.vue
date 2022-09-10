<template>
  <div class="app_container">
    <h1 class="app_title">Remember Me</h1>
    <p class="app_text">Запам'ятай та відкрий всі зелені клітинки</p>
  </div>
  <BoardGame />
</template>
<script>
import BoardGame from "./components/BoardGame.vue";
export default {
  components: {
    BoardGame,
  },
};
</script>

<style lang="scss">
#app {
  text-align: center;
}
.app {
  &_container {
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
    margin-top: 40px;
  }
}
</style>
