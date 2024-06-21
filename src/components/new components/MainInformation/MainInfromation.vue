<script setup lang="ts">
import HeaderName from './MainInformationComponents/HeaderName.vue';
import MainInfromationAbout from './MainInformationComponents/MainInfromationAbout.vue'
import SkillsWrapper from './MainInformationComponents/SkillsWrapper.vue'
</script>

<template>
  <section class="main-information">
    <HeaderName/>
    <MainInfromationAbout/>
    <SkillsWrapper/>
  </section>
</template>

<style lang="scss" scoped>
.main-information {
  box-sizing: border-box;
  margin-top: 62px;
  max-width: 961px;
  min-width: 100%;
}
</style>
