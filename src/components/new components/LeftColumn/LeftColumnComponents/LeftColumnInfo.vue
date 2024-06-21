

<template>
<article class="left-column__information">
      <ul class="column__information-list">
        <li class="left-column__information-item"><span>Возраст:</span><span>26</span></li>
        <li class="left-column__information-item">
          <span>Профессия:</span><span>Frontend developer</span>
        </li>
        <li class="left-column__information-item">
          <span>Телефон:</span><span>+9 (999) 000-00-00</span>
        </li>
        <li class="left-column__information-item">
          <span>Город:</span><span>Санкт-Петербург</span>
        </li>
      </ul>
    </article>
</template>

<style lang="scss" scoped>
.left-column__information{
    max-width: 349px;
    width: 95%;
    display: flex;
    justify-content: center;
    

      &-item {
          justify-content: space-between;
          display: flex;
    }
}
</style>
