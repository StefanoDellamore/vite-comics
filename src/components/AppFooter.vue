<script>
export default {
    data() {
        return {
            logoSocial: [
            "footer-facebook.png",
			"footer-periscope.png",
			"footer-pinterest.png",
			"footer-twitter.png",
			"footer-youtube.png",
            ],
        };
    },
    methods: {
        getImagePath(imgPath) {
            return new URL (imgPath, import.meta.url).href;
        }
    }
}
</script>

<template>
    <footer>

        <div class="container-2 backgruond-footer flex justify-content-center">
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

            <div class="logo-hover">
                <div id="log-dc"></div>
            </div>
        </div>
        
        <div class="container-2 flex space-beetwen background-black2">

            <div class="flex align-items">
                <button>
                    SIGN UP NOW!!
                </button>
            </div>

            <div class="flex align-items">
                <div class="text-footer">FOLLOW US</div>
                <div class="flex">
                    <img class="margin-left-10 {" v-for="(elem) in logoSocial" :src="getImagePath ('/img/' + elem)" alt="">
                </div>    
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
button {
    padding: 10px;
    border: 1px solid #1B60C5;
    background-color: #1C1C1C;
    color: white;
}
</style>
