<script setup lang="ts">
// import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
import LeftColumn from './components/new components/LeftColumn/LeftColumn.vue'
import MainInfromation from './components/new components/MainInformation/MainInfromation.vue'
import { ref } from 'vue'


</script>

<template>
  <div class="body_class">
    <div class="main">
      <LeftColumn />
      <MainInfromation />
    </div>
  </div>
</template>

<style lang="scss">
h1,
h2,
h3,
h4,
h5,
h6 {
  font-size: 25px;
  line-height: 30.5px;
}

.body_class {
  display: flex;
  box-sizing: border-box;
  justify-content: center;
  font-family: 'Avenir Next'; /* ШРИФТ ПОМЕНЯТЬ! */
  font-size: 22px;
  line-height: 27px;
}

.main {
  display: flex;
  max-width: 1600px;
  padding: 10px;
}


</style>
