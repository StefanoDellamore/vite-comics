<script>
export default {
    data() {
        return {
        };
    },
    props: {
        series: String,
        thumb: String,
        type: String
    }
}
</script>

<template>
    <div class="single-film flex wrap column">
        <div class="container-img2">
            <img :src="thumb" :alt="type">
        </div>
        <p>
        {{ series }}
        </p>
    </div>

    
</template>

<style lang="scss" scoped>
img {
    width: 100%;
}
</style>