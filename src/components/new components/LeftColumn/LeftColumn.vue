<script setup lang="ts">
import LeftColumnIMG from './LeftColumnComponents/LeftColumnIMG.vue'
import LeftColumnInfo from './LeftColumnComponents/LeftColumnInfo.vue'
import LeftColumnSkills from './LeftColumnComponents/LeftColumnSkills.vue';
import LeftColumnContacts from './LeftColumnComponents/LeftColumnContacts.vue';
</script>

<template>
  <section class="left-column">
    <LeftColumnIMG/>
    <LeftColumnInfo/>
    <LeftColumnSkills/>
    <LeftColumnContacts/>
  </section>
</template>

<style lang="scss" scoped>
.left-column {
  min-width: 360px;
  max-width: 469px;
  max-height: 950px;
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #f7f7f7;
  box-sizing: border-box;
  padding: 20px 10px 20px;
  margin: 25px 35px 0 1px;
  gap: 30px;
}
</style>
