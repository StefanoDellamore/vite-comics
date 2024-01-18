<script>
export default {
    data() {
        return {
            navElem: [
                "digital comics",
                "dc merchandise",
                "subcription",
                "comics shop locator",
                "dc powe visa"
            ],
            text:"contenuto da aggiungere"
        };
    },
    methods: {

    }
}
</script>

<template>
    <main>
        <div class="container-2 background-black">
            <h1>
                {{text}}
            </h1>
        </div>
        <div>
            <ul class="flex justify-content-center background-blu">
                <li v-for="(elem, i) in navElem" class="flex align-items">
                    <div class="container-img">
                        <img src="/img/dc-logo.png" alt="">
                    </div>
                    <a class="color-white" href="">
                        {{ elem }}
                    </a>
                </li>
            </ul>
        </div>

        <div class="container flex ">
            <div>
                <ul>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
            </ul>

            <ul>
                <li>prova</li>
                <li>prova</li>
            </ul>
            </div>
            

            <ul>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
            </ul>

            <ul>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
            </ul>
        </div>
    </main>
</template>

<style lang="scss" scoped>
</style>
