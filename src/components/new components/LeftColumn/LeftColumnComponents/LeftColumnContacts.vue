<template>
<article class="left-column__contacts">
    <a href="https://t.me/veryangryhuman" target="_blank" class="left-column__contacts-social">
        <img src="/src/assets/telegram-icon.png" alt="Иконка телеграма" />
        <span class="Telegram">Telegram</span>
    </a>

    <a href="https://vk.com/asdxqwerty" target="_blank" class="left-column__contacts-social">
        <img src="/src/assets/vk-icon.png" alt="Иконка ВКонтакте" />
        <span>ВКонтакте</span>
    </a>

    <a href="mailto:botoliver556@gmail.com" target="_blank" class="left-column__contacts-social">
        <img src="/src/assets/gmail-icon.png" alt="Иконка Gmail" />
        <span>Gmail</span>
    </a>
</article>

</template>

<style lang="scss" scoped>

.left-column__contacts {
  max-width: 349px;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  display: flex;

    &-social {
      align-items: center;
      max-width: 150px;
      max-height: 45px;
      text-decoration: none;
      color: rgb(0, 0, 0);
      display: flex;

        > img {
          max-height: 30px;
          margin-right: 5px;
          max-width: 30px;
        }
    }
}



</style>
