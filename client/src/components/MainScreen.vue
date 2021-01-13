<template>
  <div class="container">
    <div class="row">
      <TopMenu />
    </div>
    <div class="row">
      <GameScreen />
    </div>
    <div class="row">
      <BottomMenu />
    </div>
  </div>
</template>

<script>
import TopMenu from './screen/menus/TopMenu.vue'
import BottomMenu from './screen/menus/BottomMenu.vue'
import GameScreen from './screen/GameScreen.vue'

export default {
  name: 'MainScreen',
  props: {
    msg: String
  },
  components: {
    TopMenu,
    BottomMenu,
    GameScreen
  }
}
</script>

<style scoped></style>
