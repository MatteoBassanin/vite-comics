<template>
    <div class="big_cards_wrapper d_flex flex_wrap">
        <div v-for="(element, index) in linkCard" class="card_wrapper" :key="index">
            <img :src="element.thumb" alt="">
            <h5>{{ element.series }}</h5>
        </div>

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
    padding: 20px;
}

h5 {
    font-size: 12px;
}
</style>