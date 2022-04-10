<template>
    <header class="header">
        <div class="header_inner">
            <div class="header_inner-name">QPICK</div>
            <div class="header_inner-menu">
                <div class="header_inner-menu-favorite">
                    <img src="src\img\header-favorite.svg">
                    <div class="circle">1</div>
                </div>
                <div class="header_inner-menu-cart">
                    <img src="src\img\header-cart.svg">
                    <div class="circle">1</div>
                </div>
                
            </div>
        </div>
    </header>
</template>

<script>

export default {
    
}
</script>

<style>
    .header {
        height: 60px;
    }

    .header_inner {
        height: 60px;
        margin-left: 10%;
        margin-right: 10%;
        top: 0%;
        bottom: 0%;
        padding: 0 16.84px 0 0;
    }

    .header_inner-name {
        left: 0%;
        display: inline-block;
        padding-top: 15px;
        padding-bottom: 15px;
        font-family: 'Montserrat';
        font-style: normal;
        font-weight: 700;
        font-size: 25px;
        line-height: 30px;
    }

    .header_inner-menu {
        display: inline-block;
        float: right;
        padding-top: 20px;
    }


    .header_inner-menu-favorite {
        display: inline-block;
        padding-right: 15px;
        padding: 0px;
        Position: relative;
    }


    .header_inner-menu-cart {
        display: inline-block;
        margin-left: 15px;
        padding: 0px;
        position: relative;
    }    
    .circle {
        position: absolute;
        top: -10px;
        right: -10px;
        width: 17.4px;
        height: 17.4px;
        border-radius: 50%;
        text-align: center;
        background: #FFA542;
    
        font-family: 'Montserrat';
        font-style: normal;
        font-weight: 500;
        font-size: 15px;
        line-height: 18px;
        text-align: center;
    
        color: #FFFFFF;
    }
</style>