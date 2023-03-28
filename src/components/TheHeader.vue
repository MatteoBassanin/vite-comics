<template>
    <div class="header_wrapper d_flex space_between w_80_auto">
        <div class="logo_wrapper">
            <img class="logo" src="/img/dc-logo.png" alt="">
        </div>

        <nav class="navbar d_flex">
            <ul class="d_flex ">
                <li v-for="element in linkArrayTop" class="navbar_link"><a href="#">{{ element.name }}</a></li>
            </ul>
        </nav>

    </div>
</template>


<style scoped>
img {
    padding: 5px;
}

ul {
    padding-top: 30px;
}

.logo {
    height: 70px;
}

.navbar_link a {
    text-decoration: none;
    color: black;
    padding: 0 10px;
}


li:hover a {
    color: #2881F6;
}

li:hover {
    border-bottom: 3px solid #2881F6;
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