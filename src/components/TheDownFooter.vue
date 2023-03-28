<template>
    <div class="container ">
        <div class="bottom_wrapper d_flex space_between align_center w_80_auto">

            <div class="left_side">
                <div class="button"><a href="#">SIGN-UP NOW!</a></div>
            </div>


            <div class="right_side d_flex align_center">
                <h4>FOLLOW US</h4>
                <ul class="d_flex">
                    <li v-for="element in linkFooterDown"><a href="#"><img src={{ element.img }} alt=""></a></li>

                </ul>
            </div>
        </div>

    </div>
</template>

<style scoped>
.container {
    background-color: #303030;
    height: 100px;

}

.bottom_wrapper {
    height: 100%;
}

li {
    list-style: none;
    padding: 0 10px;
}

.button {
    border: 1px solid blue;
    padding: 10px;
}

.button a {
    text-decoration: none;
    color: white;
}
</style>

<script>

export default {
    data() {
        return {
            linkFooterDown: [
                {
                    img: "public/img/footer-facebook.png",
                },
                {
                    img: "public/img/footer-twitter.png",
                },
                {
                    img: "public/img/footer-youtube.png",
                },
                {
                    img: "public/img/footer-pinterest.png",
                },
                {
                    img: "public/img/footer-periscope.png",
                },
            ]
        }
    },


    // methods: {
    //     getImagePath: function (img) {
    //         return new URL(`public/${img}`, import.meta.url).href;
    //     }
    // }
};
</script>