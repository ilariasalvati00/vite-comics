<script setup></script>

<template>
    <div class="container">
        <div class="img-container">
            <img src="../assets/dc-logo.png" alt="">
        </div>
        <div class="a-container">
            <a href="">CHARACTERS</a>
            <a href="">COMICS</a>
            <a href="">MOVIES</a>
            <a href="">TV</a>
            <a href="">GAMES</a>
            <a href="">COLLECTIBLES</a>
            <a href="">VIDEOS</a>
            <a href="">FANS</a>
            <a href="">NEWS</a>
            <a href="">SHOP</a>
        </div>
    </div>
</template>

<style scoped>
* {
    font-family: sans-serif;
}

.container {
    width: 80%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.img-container {
    width: 5%;
}

img {
    width: 100%;
}

.a-container {
    display: flex;
    justify-content: space-between;
    width: 60%;
}

a {
    color: #303030;
    text-decoration: none;
    font-size: 10pt;
}

a:hover {
    color: #0282f9;
}
</style>