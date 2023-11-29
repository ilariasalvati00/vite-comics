<script setup>
defineProps({
    thumb: String,
    title: String
})
</script>

<template>
    <div>
        <div class="immagine" :style="{ 'background-image': 'url(' + thumb + ')' }"></div>
        <p>{{ title }}</p>
    </div>
</template>

<style scoped>
div {
    padding: 1rem;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
}

.immagine {
    width: 200px;
    height: 200px;
    background-position: top;
    background-size: cover;
    background-repeat: no-repeat;
}

p {
    color: white;
}
</style>
