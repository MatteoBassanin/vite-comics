<template>
    <div class="container">
        <div class="main_top"></div>
        <div class="main_bot">
            <div class="blue_botton top"><a href="#">CURRENT SERIES</a></div>
            <div class="cards_container w_80_auto">
                <TheCard :linkCard="comicArray" />
            </div>
            <div class="blue_botton bot"><a href="#">LOAD MORE</a></div>

        </div>

    </div>
</template>


<style scoped>
.main_top {
    background-image: url("public/img/jumbotron.jpg");
    height: 400px;
}

.main_bot {
    min-height: 650px;
    background-color: #1C1C1C;
}

.blue_botton {
    background-color: #2881F6;
    border: 1px solid #2881F6;
    width: 150px;
    text-align: center;
    padding: 5px;
    position: relative;
}

.top {
    bottom: 15px;
    left: 185px;
}

.bot {
    transform: translate(-50%);
    left: 50%;
    top: 50px;

}

.blue_botton a {
    text-decoration: none;
    color: white;
}
</style>

<script>
import TheCard from './TheCard.vue';


export default {

    components: {
        TheCard
    },


    name: "TheMain",
    data() {
        return {
            comicArray: [
                {
                    "thumb": "https://static.dc.com/2023-03/LEGIONOB_Cv1_00111_DIGITAL.jpg?w=640",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/BA_Cv9_00911_DIGITAL.jpg?w=640",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/ST_GH_Cv3_00311_DIGITAL.jpg?w=640",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/MS30A_Cv1_00111_DIGITAL.jpg?w=640",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/MS30A_Cv1_00111_DIGITAL.jpg?w=640",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/BMSMWF_Cv13_01311_DIGITAL.jpg?w=640",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/NTW_Cv102_10211_DIGITAL-1.jpg?w=640",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/FLS_Cv795_79511_DIGITAL.jpg?w=640",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/DCConnect_35-CVR.jpg?w=640",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/ROBIN_v3%20%28Cover%29.jpg?w=640",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/LP-ROTG_Cv1_00111_DIGITAL.jpg?w=640",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/2023-03/SM_LOST_Cv1_00111_DIGITAL.jpg?w=640",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }
            ]
        }
    }
}

</script>