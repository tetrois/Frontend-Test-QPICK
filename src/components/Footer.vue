<template>
    <footer class="footer">
        <div class="footer_name">QPICK</div>
        <div class="footer_nav-menu">
            <div class="footer_link">
                <a href="">Избранное</a>
            </div>
            <div class="footer_link">
                <a href="">Корзина</a>
            </div>
            <div class="footer_link">
                <a href="">Контакты</a>
            </div>
        </div>
        <div class="footer_nav-menu">
            <div class="footer_link">
                <a href="">Условия сервиса</a>
            </div>
            <div class="footer_language">
                <div class="footer_language-pic">
                    <img src="src/img/footer-planet.svg">
                </div>
                <div class="footer_language-change checked">Рус</div>
                <div class="footer_language-change">Eng</div>
            </div>
        </div>
        <div class="footer_social">
            <div class="footer_social-link">
                <img src="/src/img/footer-social-vk.svg" alt="">
            </div>
            <div class="footer_social-link">
                <img src="/src/img/footer-social-tg.svg" alt="">
            </div>
            <div class="footer_social-link">
                <img src="/src/img/footer-social-whatsapp.svg" alt="">
            </div>
        </div>
    </footer>
</template>

<script>

export default {
    
}
</script>

<style>
    .footer {
        
        width: 80%;
        height: 149px;
        margin-left: 10%;
        margin-right: 10%;
        display: flex;
        justify-content: space-between;

        background: #FFFFFF;
        box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);
        border-radius: 30px 30px 0px 0px;
    }
    .footer_name {
        font-family: 'Montserrat';
        font-style: normal;
        font-weight: 700;
        font-size: 25px;
        line-height: 30px;
        color: #101010;
        padding: 29px 0 0 29px;
    }

    .footer_nav-menu {
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        
    }

    .footer_link > a {
        font-family: 'Montserrat';
        font-style: normal;
        font-weight: 400;
        font-size: 17px;
        line-height: 21px;
        color: #000000;
        text-decoration: none;  
        
    }

    .footer_language {
        display: flex;
        flex-direction: row;
    }
    .footer_language-pic {
        padding: 17px 17px 17px 0;
    }

    .footer_language-change {
        font-family: 'Montserrat';
        font-style: normal;
        font-weight: 500;
        font-size: 15px;
        line-height: 18px;
        padding: 17px 17px 17px 0;
    }

    .footer_language-change.checked {
        color: #FFA542;
        font-weight: 700;
    }

    .footer_social {
        display: flex;
        flex-direction: row;
        align-content: flex-end;
        padding: 29px 29px 0 0;
    }

    .footer_social-link {
        margin: 0 0 0 17.9px;
    }
</style>