<script>
export default {
    data() {
        return {
        };
    },
    props: {
        name: String,
        image: String,
    }
}
</script>

<template>
        <div class="single-icon flex align-items">

            <div class="container-img">
                <img :src="image" alt="">
            </div>
            <p>
                {{ name }}
            </p>    
        </div>  
    
</template>

<style lang="scss" scoped>
img {
    width: 100%;
}

p{
    color: white;
    margin-left: 10px;
}
</style>