<script>
export default {
    data() {
        return {
            immagineAbs: 'https://picsum.photos/1900/500',
            immagineRel: '/immagine-esempio.jpg'
        }
    }
}
</script>

<template>
    <img :src="immagineAbs">
    <img :src="immagineRel">
</template>

<style scoped>
img {
    width: 100%;
    height: 400px;
    object-fit: cover;
}
</style>