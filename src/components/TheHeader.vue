<template>
    <div class="header_wrapper d_flex space_between w_80_auto">
        <div class="logo_wrapper">
            <img class="logo" src="/img/dc-logo.png" alt="">
        </div>

        <nav class="navbar d_flex align_center">
            <ul class="d_flex ">
                <li v-for="element in linkArrayTop" class="navbar_link"><a href="#">{{ element.name }}</a></li>
            </ul>
        </nav>

    </div>
</template>


<style scoped>
.header_wrapper {
    padding: 20px 0;

}

.logo {
    height: 70px;
}

.navbar_link a {
    text-decoration: none;
    color: black;
    padding: 0 10px;
}

.navbar_link {
    list-style: none;
}
</style>

<script>
export default {
    data() {
        return {
            linkArrayTop: [
                {
                    name: "CHARACTERS",
                },
                {
                    name: "COMICS",
                },
                {
                    name: "MOVIES",
                },
                {
                    name: "TV",
                },
                {
                    name: "GAMES",
                },
                {
                    name: "COLLECTIBLES",
                },
                {
                    name: "FANS",
                },
                {
                    name: "NEWS",
                },
                {
                    name: "SHOP",
                },

            ]
        }
    }
};


</script>