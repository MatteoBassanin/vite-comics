<template>
    <div class="wrapper d_flex align_center">
        <div class="action_list_wrapper w_80_auto ">
            <ul class="d_flex align_center justify_center">
                <li v-for="element in shopArray" class="d_flex align_center"><img :src="element.picture" alt=""><a
                        href="#">{{
                            element.name }}</a></li>
            </ul>
        </div>
    </div>
</template>


<style scoped>
.wrapper {
    background-color: #2881F6;
    height: 150px;
}

a {
    color: white;
    text-decoration: none;
    margin: 0 30px;
    font: 12px;
}

li {
    padding: 0 60px;
}

ul {
    list-style: none;
}

img {
    height: 50px;
}
</style>


<script>

export default {
    data() {
        return {
            shopArray: [
                {
                    name: "DIGITALS COMICS",
                    picture: "public/img/buy-comics-digital-comics.png",
                    alt: ""
                },
                {
                    name: "DC MERCHANDISE",
                    picture: "public/img/buy-comics-merchandise.png",
                    alt: ""
                },
                {
                    name: "SUBSCRIPTION",
                    picture: "public/img/buy-comics-subscriptions.png",
                    alt: ""
                },
                {
                    name: "COMIC SHOP LOCATOR",
                    picture: "public/img/buy-comics-shop-locator.png",
                    alt: ""
                },
                {
                    name: "DC POWER VISA",
                    picture: "public/img/buy-dc-power-visa.svg",
                    alt: ""
                },

            ]
        }
    }
};
</script>