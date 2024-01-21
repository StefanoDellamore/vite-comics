<script>
export default {
    data() {
        return {
            navElem: [
                "characters",
                "comics",
                "movies",
                "tv",
                "games",
                "collectibles",
                "videos",
                "fans",
                "news",
                "shop",
            ]
        };
    },
    methods: {

    }
}
</script>

<template>
    <header>
        
        <div class="container flex space-beetwen align-items">
            <div class="logo">
                <img src="/img/dc-logo.png" alt="DC-logo">
            </div>

            <nav>
                <ul class="flex">
                    <li v-for="(elem, i) in navElem">
                        <a class="color-black" href="">
                            {{ elem }}
                        </a>
                    </li>                    
                </ul>
        </nav>
        </div>

        
    </header>
</template>

<style lang="scss" scoped>
@use"../assets/scss/main.scss" as *;
a:hover {
    color:blue ;

}
</style>
