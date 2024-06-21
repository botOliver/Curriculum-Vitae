<template>
<article class="left-column__skills">
    <ul class="left-column__skills-list">
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>TypeScript</li>
        <li>Vue2</li>
        <li>Vue3</li>
        <li>Vite</li>
        <li>NPM</li>
        <li>GIT</li>
        <li>Figma</li>
        <li>Docker</li>
    </ul>
</article>
</template>

<style lang="scss" scoped>
.left-column__skills-list {
    max-width: 349px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 10px;

    >li{
        color: #ffffff;
        padding: 5px;
        font-size: 18px;
        background-color: #7b7b7b;
    }
}
</style>
