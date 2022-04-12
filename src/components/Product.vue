<template>
    <div class="product">
        <div class="image">
            <img class="product-img" :src="item.img">
        </div>
        <div class="product-info">
            <div class="product-info-left">
                <div class="product-name">{{ item.title }}</div>
                <div class="product-rating">
                    <div class="product-img-star">
                        <img src="src/img/rating-star.svg" alt="">
                    </div>
                    <div class="product-rating-score">{{ item.rate }}</div>
                </div>

            </div>
            <div class="product-info-right">
                <div class="product-price">{{ item.price }} ₽</div>
                <div class="product-price-old" v-if="item.priceOld">{{ item.priceOld }} ₽</div>
                <div class="product-btn-buy">Купить</div>
            </div>

        </div>
    </div>
</template>

<script>
export default {
    props: {
        item: Object
    },
    data() {
        return {}
    },
}
</script>

<style>
.product {
    width: 350px;
    height: 407px;
    margin-bottom: 30px;
    background: #FFFFFF;
    box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);
    border-radius: 30px;
}

.product-img {
    width: "219.61px";
    height: "237.07px";
}
.image {
    padding-top: 15.07px;
    padding-left: 65.88px;
    padding-right: 64.51px;
}

.product-info {
    padding-top: 54.36px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

.product-info-left {
    display: flex;
    flex-direction: column;
    align-content: flex-start;
    justify-content: space-between;
    padding-left: 22px;
}

.product-info-right {
    display: flex;
    flex-direction: column;
    align-content: space-around;
    justify-content: space-between;
}

.product-name {
    
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 600;
    font-size: 17px;
    line-height: 21px;
    color: #1C1C27;
}

.product-price {
    /* display: inline-block;
    float: right;
    padding-right: 21px;
    padding-bottom: 0px; */

    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 600;
    font-size: 17px;
    line-height: 21px;
    color: #FFA542;
}

.product-rating {
    display: flex;
    flex-direction: row;
    /* padding-left: 21.96px;
    padding-bottom: 32.63px;
    padding-top: 9.98px;
    padding-bottom: 32.6px; */
}

.product-img-star {
}

.product-rating-score{
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 600;
    font-size: 17px;
    color: #838383;
    padding-left: 10px;
    
}

.product-price-old {
    
    /* text-align: right;
    padding-right: 28px;
    padding-top: 0.13px; */
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 600;
    font-size: 13px;
    line-height: 16px;
    text-decoration-line: line-through;
    color: #FFCE7F;
    
}

.product-btn-buy {
    /* display: inline-block;
    float: right; */
    padding-right: 18px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 600;
    font-size: 17px;
    line-height: 21px;
    color: #000000;
}
</style>