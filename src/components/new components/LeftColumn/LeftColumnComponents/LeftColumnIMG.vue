<template>
    <img
    class="left-column__image"
    alt="моя фотография"
    src="/src/assets/photo_2024-02-24_21-03-13 — копия.jpg"
    />

    <h2 class="left-column__header">Пак Герман</h2>

    <h2 class="left-column__about">Junior frontend developer</h2>
</template>

<style lang="scss" scoped>
.left-column__image {
    display: block;
    width: 82%;
    border-radius: 50%;
    filter: grayscale(100%);
    box-shadow: 0px 7px 11px 0px #74747480;
}

.left-column__header {
    display: none;
}
</style>
