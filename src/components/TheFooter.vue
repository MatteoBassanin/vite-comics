<template>
    <div class="footer_wrapper">
        <div class="inner_wrapper w_80_auto d_flex space_between">
            <div class="left_side">
                <div class="list_wrapper d_flex space_between">
                    <div class="first col">
                        <h3>DC COMICS</h3>
                        <ul>
                            <li v-for="element in linkArrayBotFirstLeft"><a href="#">{{ element.name }}</a></li>

                        </ul>
                        <h3>SHOP</h3>
                        <ul>
                            <li v-for="element in linkArrayBotSecondLeft"><a href="#">{{ element.name }}</a></li>

                        </ul>
                    </div>
                    <div class="second col">
                        <h3>DC</h3>
                        <ul>
                            <li v-for="element in linkArrayMiddle"><a href="#">{{ element.name }}</a></li>

                        </ul>
                    </div>
                    <div class="third col">
                        <h3>SITES</h3>
                        <ul>
                            <li v-for="element in linkArrayBotRight"><a href="#">{{ element.name }}</a></li>

                        </ul>

                    </div>
                </div>
            </div>
            <div class="right_side p_relative">
                <!-- <img class="big_logo p_relative" src="public/img/dc-logo-bg.png" alt=""> -->
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            linkArrayBotFirstLeft: [
                {
                    name: "Characters",
                },
                {
                    name: "Comics",
                },
                {
                    name: "Movies",
                },
                {
                    name: "TV",
                },
                {
                    name: "Games",
                },
                {
                    name: "Videos",
                },
                {
                    name: "News",
                },
            ],
            linkArrayBotSecondLeft: [
                {
                    name: "Shop DC",
                },
                {
                    name: "Shop DC Collectables",
                },
            ],
            linkArrayMiddle: [
                {
                    name: "Terms Of Use",
                },
                {
                    name: "Privacy policy(new)",
                },
                {
                    name: "Ad Choices",
                },
                {
                    name: "Advertising",
                },
                {
                    name: "Jobs",
                },
                {
                    name: "Subscriptions",
                },
                {
                    name: "Talent Workshops",
                },
                {
                    name: "CPSC Certificates",
                },
                {
                    name: "Ratings",
                },
                {
                    name: "Shop Help",
                },
                {
                    name: "Contact Us",
                },
            ],
            linkArrayBotRight: [
                {
                    name: "DC",
                },
                {
                    name: "MAD Magazine",
                },
                {
                    name: "DC Kids",
                },
                {
                    name: "DC Universe",
                },
                {
                    name: "Dc Power Visa",
                },
            ],
        }
    }
};
</script>

<style scoped>
.footer_wrapper {
    background-image: url("/img/footer-bg.jpg");
    height: 400px;

}


.right_side {
    background-image: url("/img/dc-logo-bg.png");
    background-position: center;
    background-repeat: no-repeat;
    height: 400px;
    width: 560px;

}



ul {
    list-style: none;
}

.col {
    padding: 20px;
}

a {
    text-decoration: none;
    color: grey;
}

h3 {
    color: white;
}

.big_logo {
    bottom: 90px;
}
</style>