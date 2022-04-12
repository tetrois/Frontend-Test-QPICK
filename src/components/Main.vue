<template>
    <main class="main">
        <div class="product-category">
            <p class="product-category-name">Наушники</p>
            <div class="product-category-items">

                <Product  v-for="(headphone, index) in headphones"
                    :item="headphone"
                    :key="index"

                ></Product>

            </div>
        </div>
    </main>
</template>

<script>
import Product from '@/components/Product.vue';

export default {
    data() {
        return {
            headphones: [
                {
                    img: "src/img/p1.png",
                    title: "Apple BYZ S852I",
                    price: "2927",
                    priceOld: "3200",
                    rate: "4.7"
                }
            ]
        }
    },
    components: {
        Product
    }
}
</script>

<style>
    .main {
        margin-left: 11%;
        margin-right: 11%;
        flex: 1 1 auto;   
    }
</style>