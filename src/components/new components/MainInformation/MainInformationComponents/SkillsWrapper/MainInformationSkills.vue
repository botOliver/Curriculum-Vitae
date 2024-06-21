<script setup lang="ts">

</script>

<template>
        <div class="main-information__job">
          <h3>Медицинский брат</h3>
          <div class="main-information__job-date">Апрель 2019 - Октябрь 2023</div>
          <p>ГБУЗ Ленинградская областная клиническая больница, Санкт-Петербург.</p>

          <div class="main-information__responsibilities">
            <div class="main-information__responsibilities-point"></div>
            <span>Доврачебная медицинская помощь</span>
          </div>

          <div class="main-information__responsibilities">
            <div class="main-information__responsibilities-point"></div>
            <span>Руководство младшим мед. персоналом</span>
          </div>

          <div class="main-information__responsibilities">
            <div class="main-information__responsibilities-point"></div>
            <span>Организация ухода за больным</span>
          </div>
        </div>
</template>

<style lang="scss" scoped>
.main-information__job {
  max-width: 440px;

    h3 {
      margin-bottom: 22px;
    }

    p {
      margin-block-start: 1em;
      margin-block-end: 1em;
      margin-inline-start: 0px;
      margin-inline-end: 0px;
      unicode-bidi: isolate;
      display: block;
    }

    .main-information__responsibilities{
      display: flex;

        &-point{
          margin: 7px 5px 0 0;
          width: 10px;
          height: 10px;
          border-radius: 50%;
          background-color: #7b7b7b;
        }
    }
}
</style>
