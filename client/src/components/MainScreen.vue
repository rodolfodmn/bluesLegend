<template>
  <div class="hello">
    <h1>main screen</h1>
    <TopMenu />
    <BottomMenu />
    <GameScreen />
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
