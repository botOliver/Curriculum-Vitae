<script setup lang="ts">
import MainInformationSkills from './SkillsWrapper/MainInformationSkills.vue';
import MainInformationProgress from './SkillsWrapper/MainInformationProgress.vue'

</script>

<template>


<div class="main-information__skills">
  <!-- ТУТ СКИЛЛЫ И НАВЫКИ -->
    <MainInformationSkills/>
    <MainInformationProgress/>
      
      
      
    </div>
</template>

<style lang="scss" scoped>
.skills__wrapper {
  display: flex;
  margin-top: 22px;
  gap: 100px;
  display: flex;
  justify-content: space-between;
}

.main-information__skills {
  display: flex;
  justify-content: space-between;
}

/*.main-information {
  box-sizing: border-box;
  margin-top: 62px;
  max-width: 961px;
  min-width: 100%;
}*/



.main-information__personality {
  gap: 5px;
}

.main-information-levels {
  display: flex;
  justify-content: space-between;
}

.main-information__personality-line {
  position: relative;
  height: 3px;
  background-color: #d2d2d2;
  margin: 5px 7px;
}

.main-information__personality-point {
  position: absolute;
  bottom: -8px;
  width: 16px;
  height: 16px;
  background-color: #7b7b7b;
  border: 2px solid #ffffff;
  border-radius: 50%;
}

.english {
  margin-left: 59%;
}

.psychotype {
  margin-left: 65%;
}

.organization {
  margin-left: 76%;
}

.educability {
  margin-left: 70%;
}

.stress {
  margin-left: 80%;
}

.main-information__education {
  margin-top: 30px;
}
</style>
