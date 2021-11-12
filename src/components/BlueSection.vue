<template>
    <div class="blue-section-container">
        <div class="blue-section">
            <div class="buy-section" v-for="item,i in buyItems" :key="i">
                <img v-bind:src="require('../assets/' + item.fileName + '.png')" :alt="item.text">
                <div>{{ item.text.toUpperCase() }}</div>  
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'BlueSection',
    data() {
        return {
            buyItems: [
                {
                    text: 'digital comics',
                    fileName: 'buy-comics-digital-comics'
                    // '../assets/buy-comics-digital-comics.png'
                },
                {
                    text: 'dc merchandise',
                    fileName: 'buy-comics-merchandise'
                },
                {
                    text: 'subscription',
                    fileName: 'buy-comics-subscriptions'
                },
                {
                    text: 'comic shop locator',
                    fileName: 'buy-comics-shop-locator'
                },
                {
                    text: 'dc power visa',
                    fileName: 'buy-dc-power-visa'
                }
            ]
        }
    }
}
</script>

<style>

</style>