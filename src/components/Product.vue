<template>
    <div class="product">
        <div class="image">
            <img class="product-img" src="src/img/p1.png">
        </div>
        <div class="product-info">
            <div class="product-name">Apple BYZ S852I</div>
            <div class="product-price">2927 ₽</div>
            <div class="product-price-old">3527 ₽</div>

            <div class="product-rating">
                <div class="product-img-star">
                    <img src="src/img/rating-star.svg" alt="">
                </div>
                <div class="product-rating-score">4.7</div>
                <div class="product-btn-buy">Купить</div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
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
}

.product-name {
    display: inline-block;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 600;
    font-size: 17px;
    line-height: 21px;
    color: #1C1C27;
    padding-left: 21.96px;
}

.product-price {
    display: inline-block;
    float: right;
    padding-right: 21px;
    padding-bottom: 0px;

    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 600;
    font-size: 17px;
    line-height: 21px;
    color: #FFA542;
}

.product-rating {
    display: block;
    padding-left: 21.96px;
    padding-bottom: 32.63px;
    padding-top: 9.98px;
    padding-bottom: 32.6px;
}

.product-img-star {
    display: inline-block;
    float: left;
}

.product-rating-score{
    display: inline-block;
    float: left;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 600;
    font-size: 17px;
    line-height: 21px;
    color: #838383;
    padding-left: 10px;
    
}

.product-price-old {
    
    text-align: right;
    padding-right: 28px;
    padding-top: 0.13px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 600;
    font-size: 13px;
    line-height: 16px;
    text-decoration-line: line-through;
    color: #FFCE7F;
    
}

.product-btn-buy {
    display: inline-block;
    float: right;
    padding-right: 18px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 600;
    font-size: 17px;
    line-height: 21px;
    color: #000000;
}
</style>