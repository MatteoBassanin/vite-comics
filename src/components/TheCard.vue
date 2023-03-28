<template>
    <div class="big_cards_wrapper">
        <ul class="d_flex flex_wrap">
            <li v-for="(element, index) in linkCard" class="card_wrapper" :key="index">
                <a href="#"><img :src="element.thumb" alt=""></a>
                <h5><a href="#">{{ element.series }}</a></h5>
            </li>
        </ul>


    </div>
</template>


<script>
export default {
    props: {
        linkCard: Array,
    }
}
</script>

<style scoped>
img {
    width: 180px;
    height: 180px;
}

.card_wrapper {
    padding: 30px 20px;
}

h5 {
    font-size: 12px;
}

a {
    text-decoration: none;
    color: white;
}
</style>