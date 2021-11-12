<template>
    <div class="card-container">
        <a :href="'#' + item.series" class="card" v-for="item,i in dcList" :key="'card_' + i">
            <img :src="item.thumb" :alt="item.series">
            <h5>{{ item.series.toUpperCase() }}</h5>
        </a>
    </div>
</template>

<script>
import jsonData from '../database/dc-comics.json'

export default {
    name: 'CardsContainer',
    data() {
        return {
            dcList: jsonData
        }
    }
}
</script>

<style>

</style>