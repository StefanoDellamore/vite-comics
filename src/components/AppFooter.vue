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
        <div class="container-2 flex space-beetwen color-darkgray">

            <div class="flex align-items">
                <button>
                    sign
                </button>
            </div>

            <div class="flex align-items">
                <div class="text-footer">follow</div>
                <div class="flex">
                    <img class="margin-left-10 {" v-for="(elem) in logoSocial" :src="getImagePath ('/img/' + elem)" alt="">
                </div>    
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
</style>
